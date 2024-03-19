# 6 March, 2024 Group Blobfish Meeting
_this is a sample agenda for what a meeting might look like_
## Present
Alex, Bob, Sandy, Patrick, Squidworth

## Agenda

1.  Check in
    * _how did things go last week?_

        Design is on track, we've got some new features to check out and discuss.

        Code is behind, it turns out the api is not as well documented as we'd hoped.

        Goods news is that the data we needed *is* there, we just aren't sure how to get live updates.

    * _any new problems?_

        Not a problem, but we should start discussing our presentation that is due to the "funders" at the start of April.

2.  Design Discussion
        App now has clearer sections and navigation between them.
        
        What happened to idea of having multiple languages?

        If the interface is graphical (just icons) we don't need to change text there, just in content areas. 

3. Data Management
    * _how are we storing data?_

        for right now, just a static JSON in the app files, no live data connection.

        positive: don't have to worry about keeping database secure, or files behind password
        
        negative: hard to update, technically anyone with the repo could get data.

    * _are there security / privacy issues what we need to address?_

        For the prototype... no?

        But a live version will definitely need a secure, maintained database. We don't have skills to set that up, but can show in the app where a unique key would go to access live data.

4. Literature Review update
    * _11 interesting looking papers have been added to zotero_

        Are all of these relevant? Alex says Yes, but some of it probably should have been looked at before we got this far. 

        Can we still use some of the material to explain how our app works differently, or addresses issues that other people have raised?

        Like what? (I guess we have to read to find out)

    * _who wants to read and summarize?_

        Alex: let's prioritize data stuff first, he will take a look.

        Patrick: too much with the code, no time to read right now. Sandy: can skim some of the stuff on food systems to think more about how other 'tech' sollutions have been implemented.

## To Action

* Alex will take the papers on data and report back next meeting.

* Bob and Sandy will take design suggestions and update the layout to be more flexible for multilingual support -- may take two weeks, need to figure out how to implement in the software

* Patrick is still working on back-end code issues from last week, thinks there is a solution and will implement by next week. Bob on hand for support if necessary.

* Alex and Squidworth will create draft layout for presentation and assign sections to each team member to begin (Alex will edit after to create uniform design/tone for feedback)