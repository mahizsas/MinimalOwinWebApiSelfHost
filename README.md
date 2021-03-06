# MinimalOwinWebApiSelfHost

This repo contains source code for a series of articles. Each article builds upon the work done in the last. In order that the source for each article make sense in the context of the article, I have separated branches relevant to each article. 

* **Branch: Master -** Will always contain all of the changes, and be up to date with the most recent article in the series

The branches below are both referred to in [ASP.NET Web Api 2.2: Create a Self-Hosted OWIN-Based Web Api from Scratch](http://typecastexception.com/post/2015/01/11/ASPNET-Web-Api-22-Create-a-Self-Hosted-OWIN-Based-Web-Api-from-Scratch.aspx)

* **Branch: api -** The minimal example implementation of a self-hosted Web Api application using OWIN/Katana
* **Branch: ef -** Extends the example above by adding entity framework and a local, file-based database (SQL CE)

The next branch, `auth-minimal` is referred to in the post [ASP.NET Web Api: Understanding OWIN/Katana Authentication/Authorization Part I: Concepts](http://typecastexception.com/post/2015/01/19/ASPNET-Web-Api-Understanding-OWINKatana-AuthenticationAuthorization-Part-I-Concepts.aspx)

* **Branch: auth-minimal -** Adds simplified authentication examples to the previous branches. Identity is not used, and database persistence is not yet implemented for the auth stuff. 

