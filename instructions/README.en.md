# Ingenious candidates test - Domain

Hello **candidate**, before reading this README file please be sure you have completed the [README](../README.en.md). If you have any doubt please email [cherta](mailto: gchertok@ingsw.com)

## Index
* [The Problem](#the-problem)
* [Non functional requirements](#non-functional-requirements)
* [FAQ](#faq)
* [Next Step](#next-step)

## The Problem

We want to develop a web app that lists events and allow visitors to create events as well. The final app will be a very simple event board.

## User stories

### List events

As a site visitor landing on the homepage of the site I should see a list of events sorted by date.

![List events](images/event-list.png)

### Share event

As a site visitor looking at an event I should be able to click the share button. 

This button will share the event on twitter with the following text: "I will attend to [Name of the event] @ [Date of the event]"

![Share event](images/share-event.png)

### Event detail

As a visitor of the site, clicking an event should take me to the event detail view. The detail page will show all the event details like dates, location, etc.

![Event detail](images/event-detail.png)

### List featured events

As a visitor of the site on the homepage, I should see a list of featured events on the right of the screen.

![List featured events](images/highlighted-events.png)

### Login

As a user of the site, I should be able to log myself in into the site and see a backend section.

### Event list (backend)

As a logged user I should see a list of events (the same events the non-registered users see). The list should be paginated.

### Create event

As a logged user I should be able to create an event with the following data:

* Title
* Description
* Date list
* Location
* Featured (if it's featured or not)
* Imágen (URL)

![Create event](images/new-event.png)

## Non functional requirements

The app should be developed using either: ruby, ruby on rails >= 4, .net or node.js.

## FAQ

### Can I add/remove fields from the domain model?

Sure, as long as the app behaves as described in the user stories feel free to change the fields, remove or add new ones.

### I have a doubt but it's 3 am and I don't want to bother people

Don't wait for an answer, just assume whatever feels right to you and move on. If it's possible, leave a note on the README pointing the question and your best guess.

### I'm lost, I don't understand what's needs to be done

Sens an email to [cherta](mailto: gchertok@ingsw.com) and he will try to clarify.

### I have extra time and I wish to add more features to the app

Great! But please don't do it, extra features are nice but we prefer to have a few well-polished features instead of a lot of half-baked ones. Remember each feature you add may break the others.

If you really want to add more effort to the app please focus on writing **tests** or even enhance the **documentation**.

### Can I use gem / library X?

Yes, sure, you can use any library you want but not a full framework.

For example, we don't expect you to roll your own authentication system, you can use libraries like [device](https://github.com/plataformatec/devise) or [sorcery](https://github.com/NoamB/sorcery). On the other end, we don't want you to use a framework like [refinery](http://www.refinerycms.com/) or [spree](https://github.com/spree/spree) since that won't allow us to validate how you solve problems by yourself but how you master any the chosen tool.

### Do I need to come up with the views as well

Yes, you should come up with HTML views, nothing fancy is needed since we are evaluating how you manage to solve the backend issues but the app needs to be usable. 

## Next step

You can strat developing your app inside the `app` directory. Good Luck!
