# SeaMail

[Heroku link][heroku]

[heroku]:

## Minimum Viable Product
Welcome aboard! SeaMail is inspired by GMail on a Rails and Backbone framework. Users can:

<!-- This is a Markdown checklist. Use it to keep track of your progress! -->

Key Functionality:
- [ ] Create accounts
- [ ] Create sessions (log in)
- [ ] Create emails
- [ ] View emails
- [ ] View emails by folder
- [ ] Move emails to the trash
- [ ] Star/flag emails
- [ ] Send emails through a server
- [ ] Receive emails through a server

## Design Docs
* [View Wireframes][views]
* [DB schema][schema]

[views]: ./docs/views.md
[schema]: ./docs/schema.md

## Implementation Timeline

### Phase 1: User Authentication, Email Creation (~1 day)
I will implement user authentication in Rails based on the practices learned at
App Academy. By the end of this phase, users will be able to create email using
a simple text form in a Rails view. The most important part of this phase will
be pushing the app to Heroku and ensuring that everything works before moving on
to phase 2.

[Details][phase-one]

### Phase 2: Viewing Emails by Folder (~1 days)
I will add API routes to serve email data as JSON, then add Backbone
models and collections that fetch data from those routes. By the end of this
phase, users will be able to create and view emails, all inside a single Backbone 
app. Emails will also be sorted by folders.

[Details][phase-two]

### Phase 3: Star/flag Emails, Trash Folder (~0.5 days)
I will add star/flag attributes to emails as an organization tool outside of the 
folder system. I will also make an additional trash folder, with the special 
ability to `empty`, destroying the emails contained inside.

[Details][phase-three]

### Phase 4: Sending/receiving Emails (~2 days)
I will use Action Mailer to set up sending and receiving emails across the internet. 
I don't think a third-party library will be necessary for this, but I'm not sure. 
I'll try doing it with Rails at first, and if necessary, use something like `SendGrid`.

[Details][phase-four]

### Bonus Features (TBD)
- [ ] View emails by page
- [ ] Search emails by title/content
- [ ] Search emails by contact
- [ ] Chat with other users
- [ ] Attach files to emails
- [ ] Multiple sessions/session management
- [ ] User avatars

[phase-one]: ./docs/phases/phase1.md
[phase-two]: ./docs/phases/phase2.md
[phase-three]: ./docs/phases/phase3.md
[phase-four]: ./docs/phases/phase4.md
[phase-five]: ./docs/phases/phase5.md

