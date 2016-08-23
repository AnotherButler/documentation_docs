# Examples (good and bad)

Example time! Some of these are from this guide, some from the [BLE Intros](http://docs.mbed.org/docs/ble-intros/en/latest/).

## Example one

> "Introductions (to the document or sections in the document) are the only places that can link ahead, unless you're specifically telling people "you can skip this if…". Everything else should only link to something that came before it (and that the user is therefore expected to have read). Otherwise, it's likely that you're telling readers that information that's essential to understand now is explained at a later point in the document. This is a good hint that your document is not organised logically. Do not make the readers jump around."

This text is quite messy. The main point is near the end, the thing you shouldn't do is in the middle and the thing you're allowed to do is at the beginning but its wording is confused. There is no clear context to this text (even when you put it under the heading of "cross-referencing"), and because everything was mixed it wasn't clear that the exceptions to the rule are missing. This is somewhat better:

> "The information in your document should be introduced in the order in which a reader is expected to learn it; readers shouldn't have to jump between sections to put the story together. Cross-references should therefore link back (to things the reader is expected to have read already), not forward. However, there are times when forward referencing is correct:

> 1. In an introduction, where it allows people to skip to the interesting bits (it functions like a table of contents). This is true for all introductions - for the whole doc, for a chapter, for a section or set of instructions - anything.

> 2. When you're telling people "if you're already familiar with x, skip to y", giving knowledgeable readers a handy bypass of the beginners' stuff.

> 3. When saying "this is all you need for now, but we'll go further into this at a later section". Here the purpose of the reference is to allow curious readers to see ahead, not to provide essential information.

> 4. If you're sending readers to an appendix.

> 5. If you're pointing to a figure in the next page."

## Example two

> "There are two ways to treat names of functions, APIs etc: as proper nouns or as common nouns. I tend to go with treating them as proper nouns, because a proper noun is one that names a specific thing, and it doesn’t get more specific than BLE_API, does it? So we “use BLE_API”, not “use the BLE_API” (but you can say “we use the BLE API, not the WiFi API”, and you’ll note the missing underscore - we’re not using the real names here).

>Note that you can use proper nouns as common nouns. For example, if you’re using a function in a sentence, you can use just its name: “call waitForEvent()”, but if you’re reminding people that it’s a function, you need to use an article “call **the** waitForEvent() **function**”."

This is, again, a mess. Why isn't the rule fully explained before an example is given?

> "Quick flashback to school (stop screaming, it will be over soon!): there are two kinds of nouns, proper and common. A **proper** noun points to a unique thing, and it therefore takes no article (unless the article is part of the name, like the Rolling Stones). A **common** noun, on the other hand, points to a class or a non-specific instance of a class, and therefore takes an article. 

> When you're referring to APIs, functions, services and so on, the structure of the sentence is how you'll know if they're proper or common nouns. "We use BLE_API" - this is a specific API. It's a proper noun, and therefore takes no article. "We use the BLE, not WiFi, API" - you're talking about two kinds of API, and the focus is on the API. The two kinds - BLE and WiFi - are treated as common nouns, and they take the article "the". You'll note that we didn't use their proper names (BLE_API has an underscore, "the BLE API" doesn't).

> The difference is more obvious in the following two sentences: "we call waitForEvent()" and "we call the waitForEvent() function". The reason you needed the article "the" in the second sentence is that you used the word "function", rather than just the name of a specific function."

This is now much longer, but it's actually covering only the ground covered by the original example - it just does it with all the details that the original example glossed over.

## Example three

> "Before saying what the program should do (the function), we tell it when to do it. We've created a WHILE loop that will keep going so long as the condition it's checking returns the value TRUE. For the function to stop running, then, the condition it's checking will have to become false."

This is from an intro to non-developers, so I should explain what loops and conditions are before explaining how a loop uses a condition:

> "Before saying what the program should do (the function), we tell it when to do it. We use two tools to determine this: 

> * A condition that determines when to start the function, for example "when you get a new value from the thermometer". 

> * A definition of how many times to run when the starting condition is met. We can tell a function to run once, twice, to infinity or until the condition suddenly fails.

> In this example, we use the same condition to determine both when to start running and when to stop. To do this:

> * We created a WHILE loop, which is a way of saying "start this function when a condition is met, and don't stop until the condition is false". 

> * We said that the condition is that the value of ``triggerSensorPolling`` is TRUE rather than FALSE. That value is determined inside the loop. 

> If the value of ``triggerSensorPolling`` becomes FALSE, the condition will fail and the function won't run any more. This is called "exiting the loop"."

## Example four

> "Usually, _Handle Value Notifications/Indications_ are used by the server to send updated values to a subscribed client or for signaling a client that a subscribed read attribute has been updated. Because _Handle Value Notifications_ can carry the same payload as any other BLE message, is sent at the server’s discretion, and doesn't generate a response from the client, _Handle Value Notifications_ can be repurposed for transmitting low latency data from server to client."

This is the edited version:

> "Usually, the server uses ``_Handle Value Notifications/Indications_``  to send updated values to a subscribed client, or for signaling a client that a subscribed read attribute has been updated. But we can repurpose ``_Handle Value Notifications_`` for transmitting low latency data from the server to the client because ``_Handle Value Notifications_``:

> * Can carry the same payload as any other BLE message.

> * Is sent at the server’s discretion.

> * Doesn't generate a response from the client."

The two main changes are a move from passive to active voice, and bullet points instead of a long sentence. You'll also note that I moved the result ("we can repurpose…") ahead of the cause ("because it..."). This is an easier structure to follow.

## Writer's blocks aren't just for fiction writers

Got writer's block? Trying to edit yourself but keep reverting back to the original? Not to worry - generations of writers have successfully dealt with these same issues with little more than these helpful tips (and alcohol, chain smoking and criminal behaviour):

* Look away from the text for a while: work on something else, take a walk, make a cup of tea.

* Put bits of your text through Google Translate a few times. It should give you an interesting view of it (and a good giggle).

* Move to a different part of the text. 

* Try explaining it out loud to someone. They don't actually have to pay attention.

* Listen to a song you like for its lyrics.

* Spit it out, no matter how bad it is. You can edit later. Note: I don't approve of this method, because I think a first draft stays with you forever; it influences all future edits, no matter how bad it is.
