# Phase 2: Viewing Emails by Folder (~1 day)

## Rails
### Models

### Controllers
Api::EmailsController (create, destroy, index, show)

### Views
* emails/index.json.jbuilder
* emails/show.json.jbuilder

## Backbone
### Models
* Email

### Collections
* Emails

### Views
* EmailForm
* EmailShow
* EmailsIndex (composite view, contains EmailIndexItem subviews)
* EmailIndexItem

## Gems/Libraries
