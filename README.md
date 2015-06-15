# Todo Challenge

## Challenge

Build a Todo list as a mini front-end application. You don't have to use a database, the front-end is more important - you can use an appropriate data structure stored somewhere in your JavaScript (this time only!)

Core user stories:

```
As a forgetful person
I want to store my tasks
So that I don't forget them

As a person with limited time
I want to instantly be able to update my todo list (adding and changing entries)
So that I have more time to think about other things

As a person who actually gets stuff done
I want to mark my tasks as done
So that I don't do them twice
```

Here are some other user stories you may choose to implement:

```
As a person with a lot of tasks
I want to be able to filter my tasks by "All", "Active", "Complete"
So that I only see the relevant tasks

As a person who doesn't like counting by hand
I want to see a total number of tasks
So that I don't have to count

As someone who has done lots of stuff
I want to be able to clear my completed tasks
So I never see them again
```

## Unit Tests with Karma

	* initilizes with an an empty task list

	* can add an item and display that item

	* can display more than one item in the to do list
	
	* knows item is not complete

	* cannot delete an item that's not been completed

## Feature Tests with Protractor






## CI

Read the `.travis.yml` if any of the steps below don't make sense! 

* Make sure you have set up `npm test` in your `package.json` so that it runs your Karma tests
* Make sure you have your Protractor config file at `e2e/conf.js`

Good luck!
