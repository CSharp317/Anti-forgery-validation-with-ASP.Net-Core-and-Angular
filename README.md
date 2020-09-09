# ASP.NET-Core-Web-Api-Antiforgery
he use of the SameSite policy. However this feature is still “experimental” and for the use case of allowing your web api to be potentially used by anyone, using a SameSite policy would not work.  The abuse of this mechanism (i.e. the browser sending the cookies automatically) is what CSRF exploits. 
