# class 13

## This topic is important because as we work from our local all of the time, we want to be able to convert things to be able to store it in our local. By knowing this, we can be more aware of what we are doing with our code and where we are doing it.

## Local Storage and How To Use It On Websites

**Why would a developer use local storage for a web application?**
Local storage allows developers to store and retrieve data in the browser. The data stored in local storage will not expire. This means the data will persist even if the tab or the browser window is closed.

**What information should not be stored in local storage?**
Personally Identifiable Information (PII), authentication tokens, user locations and API keys, to name a few, should never be stored in the local storage.

**Local storage can store what type of data? How would you convert it to that type before storing?**
Local storage can only store string data for its keys and values. The datastore is only accessible to JavaScript within that domain. To store objects, you convert them to strings using the JSON. stringify() method. And you convert the strings into objects when you retrieve them from the localStorage using the JSON.
