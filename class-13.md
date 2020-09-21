# Explore the Tech!

In today's class, I am going to discuss the topic of ***Local Storage***, which is an interesting topic related to web development. So, _let's get started!_

### 1. Introduction:
Persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. However, web applications use Cookies, which can be used for persistent local storage of small amounts of data. But cookies do not provide the a lot of storage space on the client that persists beyond a page refresh and isn’t transmitted to the server.

### 2. _HTML5_ storage:
HTML5 Storage is based on named `key/value` pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a `string`. The data can be any type supported by JavaScript, including `strings`, `Booleans`, `integers`, or `floats`. However, the data is actually stored as a string. In this process, the following methods are used:
* `setItem()`: assigns value to a key.
* `getItem()`: retreives value from a key.
* `removeItem()`: removes a value from a key.

***Storage Event Object***
* `key`, `string`:	the named key that was added, removed, or modified.
* `oldValue`,	`any`:	the previous value (now overwritten), or null if a new item was added.
*`newValue`,	`any`:	the new value, or null if an item was removed.
* `url`, `string`: the page which called a method that triggered this change.

The `storage` event is not cancelable. From within the `handle_storage` callback function, there is no way to stop the change from occurring.

In HTML5, there is a function used to store the progress locally in the brwoser so that the progress is not lost. For example, if you're playing a game and the browser closes, you'll lose your progress. In HTML5, we can save the progress locally, within the browser itself. Make a few moves, then close the browser tab, then re-open it. If your browser supports HTML5 Storage, the demonstration page should magically remember your exact position within the game, including the number of moves you’ve made, the position of each of the pieces on the board, and even whether a particular piece is selected. In that case, a function called `saveGameState()` was used with `local storage`, where data is stored as `strings`.
