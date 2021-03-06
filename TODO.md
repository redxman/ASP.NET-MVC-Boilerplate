<h1>TODO List</h1>
<p>A list of improvements and new features to be added. Feel free to submit your own.</p>

<h2>General Improvements</h2>
<p>Improvements that can be made to all project templates.</p>
<ul>
  <li>Make use of Object Pooling code. Add note about using Object Pooling in ReadMe.html.</li>
  <li>Add <a href="https://developers.google.com/structured-data/">Google Structured Data</a>.</li>
  <li>Keep eye on <a href="http://stackoverflow.com/questions/27860618/which-http-status-codes-to-cover-for-mvc-error-handling/29282406#29282406">HTTP Status Codes</a> for codes I am not covering correctly.</li>
  <li>Update to Font Awesome 4.3.0 when they fix the .less files.</li>
  <li>Use a CDN to get Font Awesome css and fonts.</li>
</ul>

<h2>ASP.NET MVC 6</h2>
<p>A new project template in addition to the existing ASP.NET MVC 5 template, targeting ASP.NET MVC 6.</p>
<ul>
  <li>Create Boilerplate.Web.Mvc6 NuGet package and port code from Boilerplate.Web.Mvc5.</li>
  <li>Upgrade NPM, Bower, Gulp packages</li>
  <li>Decide whether to use LESS or SASS for the CSS?</li>
  <li>Finish bundling and minification using NPM, Bower and Gulp.</li>
  <li>...get this far, then think about the rest.</li>
</ul>
<p><strong>WOW, so much is missing from MVC 6 its amazing.</strong></p>
<ul>
  <li>No support for filters (FilterAttribute in MVC 5).</li>
  <li>No caching (OutputCacheAttribute in MVC 5). See <a href="http://stackoverflow.com/questions/27304210/how-do-i-apply-the-outputcache-attribute-on-a-method-in-a-vnext-project">StackOverflow</a></li>
  <li>No Atom feed without System.ServiceModel.SyndicationFeed. See <a href="https://github.com/dotnet/wcf/issues/76#issuecomment-111420491">GitHub</a></li>
  <li>No AppendTrailingSlash option for SEO. See <a href="http://stackoverflow.com/questions/27997814/lower-case-urls-and-trailing-slash/30799844#30799844">StackOverflow</a> and <a href="https://github.com/aspnet/Mvc/issues/2691">GitHub</a></li>
</ul>

<h2>ASP.NET Identity</h2>
<p>A new project template including the ASP.NET Identity package out of the box.</p>
<ul>
  <li>ASP.NET Identity Project Template.</li>
  <li>Use a better (slower) encryption algorithm like bcrypt.net, zetetic.security, scrypt (See <a href="http://blog.codinghorror.com/your-password-is-too-damn-short/">this</a> for more information.</li>
</ul>
