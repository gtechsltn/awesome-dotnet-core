# Awesome .NET Core

# Contents
+ General
+ Interview
+ Frameworks, Libraries and Tools
+ Samples
+ References
+ Articles

# General

# Education, E-Books and Interview
+ A complete computer science study plan to become a software engineer: https://github.com/jwasham/coding-interview-university
+ Freely available programming books: https://github.com/EbookFoundation/free-programming-books/
+ Vietnamese / Tiếng Việt: https://github.com/EbookFoundation/free-programming-books/blob/master/courses/free-courses-vi.md

# Frameworks, Libraries and Tools
## API

## Application Frameworks
+ ASP.NET Boilerplate - ASP.NET Boilerplate is a general purpose application framework especially designed for new modern web applications. It uses already familiar tools and implements best practices around them to provide you a SOLID development experience.
+ **ABP Framework** - Open Source Web Application Framework for ASP.NET Core (https://github.com/abpframework/abp/)
+ Abp vNext - Abp vNext is the next generation of the open source ASP.NET Boilerplate framework. It's a complete architecture and strong infrastructure to create modern web applications! Follows best practices and conventions to provide you a SOLID development experience.
+ **ASP.NET Core MVC** - The ASP.NET Core MVC framework is a lightweight, open source, highly testable presentation framework optimized for use with ASP.NET Core.
  + ASP.NET Core MVC provides a patterns-based way to build dynamic websites that enables a clean separation of concerns. It gives you full control over markup, supports TDD-friendly development and uses the latest web standards.
  + Features - ASP.NET Core MVC includes the following:
    + Routing
    + Model binding
    + Model validation
    + Dependency injection
    + Filters
    + Areas
    + Web APIs
    + Testability
    + Razor view engine
    + Strongly typed views
    + Tag Helpers
    + View Components
+ **ASP.NET MVC** - Model view controller framework for building dynamic web sites with clean separation of concerns, including the merged MVC, Web API, and Web Pages w/ Razor.
+ ASP.NET Zero - Base solution for your next web application!
+ DNTFrameworkCore - Lightweight and Extensible Infrastructure for Building High Quality Web Applications Based on ASP.NET Core.
+ DotnetSpider - DotnetSpider, a .NET Standard web crawling library similar to WebMagic and Scrapy. It is a lightweight ,efficient and fast high-level web crawling & scraping framework for .NET.
+ **EquinoxProject** - Full ASP.NET Core 5 application with DDD, CQRS and Event Sourcing concepts (https://github.com/EduardoPires/EquinoxProject)
+ ExcelDataReader - Lightweight and fast library written in C# for reading Microsoft Excel files.
+ Kledex - .NET Standard framework to create simple and clean design. Advanced features for DDD, CQRS and Event Sourcing.
+ orleans - Orleans is a cross-platform framework for building distributed applications with .NET.
+ ServiceStack - Thoughtfully architected, obscenely fast, thoroughly enjoyable web services for all https://servicestack.net.
+ Steeltoe OSS - .NET toolkit for common microservice patterns.
+ Strathweb.TypedRouting.AspNetCore - A library enabling strongly typed routing in ASP.NET Core MVC projects.
+ X.PagedList - Library for easily paging through any IEnumerable/IQueryable in ASP.NET/ASP.NET Core.

## Application Templates
+ TemplateOnionAPI - https://github.com/workcontrolgit/TemplateOnionAPI
+ Skoruba.IdentityServer4.Admin - The administration for the IdentityServer4 and Asp.Net Core Identity (https://github.com/skoruba/IdentityServer4.Admin)

## Authentication and Authorization
+ **OAuth 2.0 and OpenID Connect** (https://pragmaticwebsecurity.com/courses/introduction-oauth-oidc.html)
  + npm package for OpenID Connect, OAuth Code Flow with PKCE, Refresh tokens, Implicit Flow (https://github.com/damienbod/angular-auth-oidc-client)
+ **Scott Brady** - Scott Brady - Identity & Access Control (https://www.scottbrady91.com/Identity-Server)
+ **IdentityServer4** - OpenID Connect and OAuth 2.0 Framework for ASP.NET Core (https://github.com/IdentityServer/IdentityServer4)
  + **Skoruba.IdentityServer4.Admin** - The administration for the IdentityServer4 and Asp.Net Core Identity (https://github.com/skoruba/IdentityServer4.Admin)
  + An ASP.NET Core IdentityServer4 Identity Template with Bootstrap 4 and Localization (https://github.com/damienbod/IdentityServer4AspNetCoreIdentityTemplate)
  + OpenID Connect Code / Implicit Flow with Angular and ASP.NET Core 5 IdentityServer4 (https://github.com/damienbod/AspNet5IdentityServerAngularImplicitFlow)
  + ASP.NET Core MVC application using API, OpenID Connect Hybrid flow , second API, Code Flow with PKCE (https://github.com/damienbod/AspNetCoreHybridFlowWithApi)
  + JPProject.IdentityServer4.AdminUI - Jp Project Free Admin Panel for IdentityServer4 administration (https://github.com/brunohbrito/JPProject.IdentityServer4.AdminUI)
  + User Management with IDS4 and a Custom Database: https://anexinet.com/user-management-with-ids4-and-a-custom-database/
+ **Web API Authorization in ASP.NET Core with IdentityServer4**
  + Securing an ASP.NET Core API which uses multiple access tokens (https://damienbod.com/2020/12/03/securing-an-asp-net-core-api-which-uses-multiple-access-tokens/)
  + Securing a Web API using multiple token servers (https://damienbod.com/2019/10/25/securing-a-web-api-using-multiple-token-servers/)
+ Simple sample of an IdentityServer4-based authentication server for ASP.NET Core (https://github.com/mjrousos/IdentityServer4Authentication)
+ **Implementing Cookies Authentication in ASP.NET Core** (https://github.com/ezzylearning/AspNetCoreCookiesAuthDemo)
+ Thinktecture **IdentityServer2** is a light-weight security token service built with .NET 4.5, MVC 4, Web API and WCF. (https://github.com/IdentityServer/IdentityServer2)
+ Acronym
  + Single Sign-On (**SSO**)
  + Secure Token Service (**STS**)
  + OAuth 2.0 & OpenID Connect (**OIDC**)
  + IdentityServer4 (**IdSrv4**) & RS256
  + Proof-Key for Code Exchange (**PKCE**)
  + JSON Web Encryption (**JWE**)
  + Elliptical Curve Cryptography (**ECC**)
  + Elliptical Curve Digital Signing Algorithms (**ECDSA**)

## Bundling and Minification

## Caching

## CMS
+ **Squidex** - Headless CMS and Content Managment Hub (https://github.com/Squidex/squidex)
+ **Lin CMS** - A simple and practical CMS implemented by ASP.NET Core 5 (https://github.com/luoyunchong/lin-cms-dotnetcore/)

## Code Analysis and Metrics

## Compression

## Cryptography

## Database
+ MongoDB - Querying performance for over 10 million records
+ MongoDB - Querying performance for over 5 million records
  + Ensure it's not because of insufficient RAM and excessive paging (Đảm bảo không phải do không đủ RAM và phân trang quá nhiều)
  + Inspect the slow queries in db.system.profile and run the queries manually using explain() (Kiểm tra các truy vấn chậm trong db.system.profile và chạy các truy vấn theo cách thủ công sử dụng explain())
  + Reason about the selectivity of the query and whether it's possible to improve the query using an index at all. (Lý do về tính chọn lọc của truy vấn và liệu có thể cải thiện truy vấn bằng cách sử dụng chỉ mục hay không.)
  + Things get worse when the data is too big for the RAM... (Mọi thứ trở nên tồi tệ hơn khi dữ liệu quá lớn so với RAM...)
  + The best way to control this is to limit the number of different query types, disallow queries on low selectivity information and try to prevent random access to old data. (Cách tốt nhất để kiểm soát điều này là hạn chế số lượng các loại truy vấn khác nhau, không cho phép truy vấn thông tin có tính chọn lọc thấp và cố gắng ngăn truy cập ngẫu nhiên vào dữ liệu cũ.)
  + Making this particular query faster could be done using a compound index that contains the device type (Việc làm cho truy vấn cụ thể này nhanh hơn có thể được thực hiện bằng cách sử dụng chỉ mục kết hợp có chứa loại thiết bị)
  + I'm afraid there's no very good solution for this using mongodb at this time. (Tôi e rằng không có giải pháp nào tốt cho việc này bằng cách sử dụng mongodb vào lúc này.)
+ MongoDB - Random query performance test of mongodb database with 100 million records
+ MongoDB - 5 Successful Tips You Need to Optimize MongoDB
+ MongoDB - 7 Simple Speed Solutions for MongoDB
+ MongoDB - Indexing and MongoDB Query Performance
+ MongoDB - Add and Remove Indexes (https://www.percona.com/blog/2021/03/22/want-mongodb-performance-you-will-need-to-add-and-remove-indexes/)

## Database Drivers
+ **.NET Core Data Access** (https://devblogs.microsoft.com/dotnet/net-core-data-access/)

## Database Tools and Utilities

## Date and Time

## E-Commerce and Payments

## Exceptions

## Internationalization

## IOC

## Logging
+ log4net - log4net is a port of the excellent Apache log4j™ framework to the Microsoft® .NET runtime.
+ NLog - Advanced .NET, Silverlight and Xamarin Logging with support for structured and non structured logging.
+ serilog - Simple .NET logging with fully-structured events.
  + serilog-aspnetcore - Serilog integration for ASP.NET Core 2+.
  + Serilog.Exceptions - Serilog.Exceptions is an add-on to Serilog to log exception details and custom properties that are not output in Exception.ToString().
  + Serilog.Settings.Configuration - A Serilog configuration provider that reads from Microsoft.Extensions.Configuration.

## Mail

## Networking

## Office

## ORM
+ Entity Framework Core - Familiar developer experience to previous versions of EF, including LINQ, POCO, and Code First support.
+ **Dapper** - Simple object mapper for .NET.
+ PetaPoco - A tiny ORM-ish thing for your POCO's.
+ NPoco - Simple microORM that maps the results of a query onto a POCO object. Project based on Schotime's branch of PetaPoco.

## Profiling
+ Glimpse - Lightweight, open-source, real-time diagnostics and insights profiler for .NET. Unstable version
+ MiniProfiler - A simple but effective mini-profiler for ASP.NET websites.

## Query Builders
+ **SqlKata** - Elegant Sql Query Builder, that supports complex queries, joins, sub queries, nested where conditions, vendor engine targets and more

## Queue and Messaging
+ MediatR - Simple, unambitious mediator implementation in .NET.
+ MediatR.Extensions.Microsoft.DependencyInjection - MediatR extensions for Microsoft.Extensions.DependencyInjection.
+ Mediator.Net - A simple mediator for .Net for sending command, publishing event and request response with pipelines supported.
+ OpenCQRS - .NET Core library for DDD, CQRS and Event Sourcing with Azure Service Bus integration. Supported database providers for the Command and the Event stores are: DocumentDB, MongoDB, SQL Server, MySQL, PostgreSQL and SQLite.

## Reporting
+ FastReport - The open source report generator for .NET Core 2.x/.Net Framework 4.x. FastReport can be used in MVC, Web API applications.

## Scheduler and Cron Job
+ FluentScheduler - Automated job scheduler with fluent interface.
  + https://github.com/fluentscheduler/FluentScheduler
+ Hangfire.IO - Easy way to perform fire-and-forget, delayed and recurring tasks inside ASP.NET apps http://hangfire.io.
  + https://www.hangfire.io
  + https://github.com/HangfireIO/Hangfire
+ **Quartz.NET** - Quartz Enterprise Scheduler .NET
  + https://www.quartz-scheduler.net
  + https://github.com/quartznet/quartznet
+ Worker Service
  + https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services

## SDKs

## Security
+ aspnetcore-security-headers - Middleware for adding security headers to an ASP.NET Core application.
+ HtmlSanitizer - Cleans HTML to avoid XSS attacks.
+ reCAPTCHA - reCAPTCHA 2.0 for ASP.NET Core.
+ OwaspHeaders - .NET Core middleware for injecting the Owasp recommended HTTP Headers for increased security.
+ Security - Middleware for security and authorization of web apps.
+ SecurityHeaders - Small package to allow adding security headers to ASP.NET Core websites.

## Searching
+ AutoComplete - Persistent, simple, powerful and portable autocomplete library.
+ Elasticsearch.Net & NEST - Repository for both NEST and Elasticsearch.NET, the two official elasticsearch .NET clients.
+ ElasticsearchCRUD - Elasticsearch .NET API.
+ SearchExtensions - Advanced search capabilities for IQueryable interfaces, such as Entity Framework queries.

## Serialization
+ CsvHelper - Library to help reading and writing CSV files.
+ Newtonsoft.Json - Popular high-performance JSON framework for .NET.
+ ServiceStack.Text - JSON, JSV and CSV Text Serializers.
+ TinyCsvParser - Easy to use, easy to extend and high-performance library for CSV parsing with .NET.
+ YamlDotNet - .NET
+ YAXLib - XML Serialization Library for the .NET Framework and .NET Core. Extremely flexible and powerful.

## Testing
+ Bogus - Simple and sane fake data generator for C#. Based on and ported from the famed faker.js.
+ FakeItEasy - The easy mocking library for .NET.
+ FluentAssertions - Set of .NET extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style test.
+ nunit - NUnit test runner for .NET Core.
+ shouldly - Should testing for .NET - the way Asserting Should be! http://shouldly.readthedocs.org/en/latest
+ xUnit.net - A free, open source, community-focused unit testing tool for the .NET Framework.

## Tools
+ CommandLineUtils - Command line parsing and utilities for .NET Core and .NET Framework.
+ docfx - Tools for building and publishing API documentation for .NET projects http://dotnet.github.io/docfx
+ Fake JSON Server - Fake REST API for prototyping or as a CRUD Back End. No need to define types, uses dynamic typing. Data is stored to a single JSON file. Has authentication, WebSocket notifications, async long running operations, random generation for errors/delays and experimental GraphQL support.
+ gitignore.io - Create useful .gitignore files for your project https://www.gitignore.io.
+ json2csharp - Generate C# classes from JSON.
+ NuGetPackageExplorer - Create, update and deploy Nuget Packages with a GUI.
+ NugetVisualizer - Visualize all of the nuget packages and their corresponding versions for a set of given git repositories or folders.
+ Rin - Request/response Inspector middleware for ASP.NET Core. like Glimpse.
+ SerilogAnalyzer - Roslyn-based analysis for code using the Serilog logging library. Checks for common mistakes and usage problems.
+ SharpZipLib - #ziplib is a Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform.
+ ShareX - Free and open source program that lets you capture or record any area of your screen and share it with a single press of a key. It also allows uploading images, text or other types of files to over 80 supported destinations you can choose from. https://getsharex.com
+ SmartCode – SmartCode= IDataSource -> IBuildTask -> IOutput => Build Everything!!! (Including [Code generator]) https://github.com/dotnetcore/SmartCode
+ SmartSql - SmartSql = MyBatis in C# + .NET Core+ Cache(Memory | Redis) + R/W Splitting + PropertyChangedTrack +Dynamic Repository + InvokeSync + Diagnostics https://github.com/dotnetcore/SmartSql
+ System.CommandLine - System.CommandLine, a set of libraries for command line parsing, invocation, and rendering of terminal output.
+ X.Web.Sitemap – Simple sitemap generator for .NET and .NET Core
+ X.Web.RSS – Simple RSS Feed generator for .NET and .NET Core

## Web Frameworks
+ ReactJS.NET - .NET library for JSX compilation and server-side rendering of React components.
+ redux.NET - Predictable state container for .NET apps. Inspired by https://github.com/reactjs/redux.

## Web Socket
+ SignalR Server - Real-time web functionality for web apps, including server-side push.

## Windows Service
+ dotnet-win32-service - Set up and run as Windows Service directly from .NET Core.
+ Topshelf - Easy service hosting framework for building Windows services using .NET.

## Starter Kits
+ ASP.NET Core Starter Kit - Opinionated boilerplate for web development based on .NET Core, Kestrel, GraphQL on the backend and Babel, Webpack, React and Redux on the frontend. This boilerplate comes in both C# and F# flavors.
+ dotNetify - Simple, lightweight, yet powerful way to build real-time web apps.
+ Nucleus - Vue startup application template that uses ASP.NET Core API layered architecture at the back-end and JWT based authentication
+ .NET 5 Source Generators - MediatR - CQRS - OMG! (https://github.com/edumentab/SourceGenerator-MediatR-CQRS)
+ Onion Architecture In ASP.NET Core With CQRS (https://github.com/iammukeshm/OnionArchitecture)
+ Onion Architecture with .NET 5/.NET Core and CQRS/Event Sourcing following a DDD approach (https://github.com/pereiren/dotnet-template-onion)
+ ReactJS Starter Kit
  + ReactJS Redux Saga Axios starter kit including scss support, i18n and routing. Built on top of create-react-app project (https://github.com/sebamed/react-js-boilerplate)
  + react-redux-axios-app-starter-kit (https://github.com/Palatnyi/react-redux-axios-starter-kit)
+ MongoDB
  + Angular, Microservices and Authentication with IdentityServer, MongoDB and Docker (https://github.com/apomic80/angular-microservices-identityserver)
+ ABP Framework & MongoDB
  + Web Application Development Tutorial (https://docs.abp.io/en/commercial/latest/tutorials/book-store/part-1?UI=NG&DB=Mongo)
  + About this tutorial: In this tutorial series, you will build an ABP Commercial application named Acme.BookStore. This application is used to manage a list of books and their authors. It is developed using the following technologies:
    + MongoDB as the database provider.
    + Angular as the UI Framework.
+ Clean Architecture, Repository and Unit of Work patterns (Dapper, SQLKata, GenFu)
  + https://github.com/workcontrolgit/TemplateKissAPI
+ Angular Starter Kit for Fast Prototype
  + https://github.com/workcontrolgit/cat-toolkit-angular-starter
+ ApiResources
  + https://github.com/workcontrolgit/catnetcoreapi
+ **AWS Security Token Service (STS)** now supports enabling the global STS endpoint to issue session tokens compatible with all AWS Regions
  + https://aws.amazon.com/about-aws/whats-new/2019/04/aws-security-token-service-sts-now-supports-enabling-the-global-sts-endpoint-to-issue-session-tokens-compatible-with-all-aws-regions/
+ **IdentityServer4 Admin UI v2**
  + https://github.com/workcontrolgit/TokenProject.AdminUI
  + **DemoProject.Admin**
    + https://localhost:44303 (https://cat-token-admin.azurewebsites.net)
  + **DemoProject.Admin.Api**
    + https://localhost:44302 (https://cat-token-adminapi.azurewebsites.net)
  + **DemoProject.STS.Identity**
    + https://localhost:44310 (https://cat-token-identity.azurewebsites.net)
+ **Secure Token Service (STS) Starter Kit**
  + https://github.com/workcontrolgit/cat-toolkit-tokenservice-starter
  + **DemoProject.Admin**
    + https://localhost:44303 (https://cat-token-admin.azurewebsites.net)
  + **DemoProject.Admin.Api**
    + https://localhost:44302 (https://cat-token-adminapi.azurewebsites.net)
  + **DemoProject.STS.Identity**
    + https://localhost:44310 (https://cat-token-identity.azurewebsites.net)
+ **Oracle EF Core 5**
  + https://github.com/workcontrolgit/OracleEFCore5
+ Angular 11 Pagination 100,000+ Rows
  + https://github.com/workcontrolgit/cat-toolkit-apiresources-starter
+ **BlazorHero**
  + https://github.com/blazorhero/CleanArchitecture
+ Angular Pro Sidebar
  + https://github.com/azouaoui-med/angular-pro-sidebar

# Samples
+ CQRS: https://github.com/ezzylearning/CQRSDesignPatternDemo
+ APIs: https://github.com/ezzylearning/AspNetCore5WebApisDemo
+ ASP.NET Core SignalR: https://github.com/ezzylearning/SignalRLiveSportsDashboardDemo
+ Dapper CRUD: https://github.com/ezzylearning/AspNetCoreDapperCrudDemo
+ Database First: https://github.com/ezzylearning/AspNetCoreEfCoreDatabaseFirstDemo
+ Code First: https://github.com/ezzylearning/AspNetCoreEfCoreCodeFirstDemo
+ Third Party APIs: https://github.com/ezzylearning/ConsumeThirdPartyApisDemo (**IHttpClientFactory**)
+ Distributed Caching with Redis Cache: https://github.com/ezzylearning/AspNetCoreDistributedCachingDemo
+ In-Memory Caching: https://github.com/ezzylearning/AspNetCoreMemoryCachingDemo
+ Dapper + jQuery DataTables: https://github.com/ezzylearning/AspNetCoreDapperPagingSortingFilteringDemo
+ Bundling and Minification: https://github.com/ezzylearning/AspNetCoreBundleMinifyDemo
+ Bundling and Minification Using Gulp: https://github.com/ezzylearning/AspNetCoreBundlingWithGulpDemo
+ Authentication & Authorization with Cookies: https://github.com/ezzylearning/AspNetCoreCookiesAuthDemo

# References
+ https://github.com/thangchung/awesome-dotnet-core
+ https://github.com/thangchung/awesome-dotnet
+ https://github.com/quozd/awesome-dotnet
+ https://awesomerank.github.io/lists/thangchung/awesome-dotnet-core.html

# Articles
+ https://admin.jpproject.net/
+ https://andrewlock.net/
+ https://aspnetboilerplate.com/
+ https://benfoster.io/
+ https://binaryintellect.net/
+ https://bitoftech.net/
+ https://brockallen.com/
+ https://code-maze.com/
+ https://codewithmukesh.com/
+ https://curity.io/
+ https://damienbod.com/
+ https://dotnetcoretutorials.com/
+ https://dotnettutorials.net/
+ https://duendesoftware.com/
+ https://github.com/brunohbrito/JPProject.IdentityServer4.AdminUI
+ https://github.com/brunohbrito/JPProject.IdentityServer4.SSO
+ https://github.com/skoruba/IdentityServer4.Admin
+ https://haacked.com/
+ https://identityserver.io
+ https://identityserver4.readthedocs.io/
+ https://jasonwatmore.com/
+ https://jp-project.readthedocs.io/
+ https://jwt.io/
+ https://leastprivilege.com/
+ https://mcguirev10.com/
+ https://openid.net/
+ https://readthedocs.org/
+ https://skoruba-identityserver4-admin.readthedocs.io/
+ https://sso.jpproject.net/
+ https://stackblitz.com/
+ https://thecodeblogger.com
+ https://visualstudiomagazine.com/
+ https://volosoft.com/
+ https://wakeupandcode.com/
+ https://www.abp.io/
+ https://www.aspnetzero.com/
+ https://www.blinkingcaret.com/
+ https://www.dejanstojanovic.net/
+ https://www.dntips.ir/
+ https://www.dotnetcurry.com/
+ https://www.dotnettricks.com/
+ https://www.exceptionnotfound.net/
+ https://www.ezzylearning.net/
+ https://www.fullstackmark.com/
+ https://www.hanselman.com/
+ https://www.infoq.com/ 
+ https://www.jerriepelser.com/
+ https://www.learnrazorpages.com/
+ https://www.mikesdotnetting.com/
+ https://www.red-gate.com/
+ https://www.scottbrady91.com/
+ https://www.sitelike.org/similar/identityserver.io/
+ https://www.talkingdotnet.com/
+ https://www.tutorialsteacher.com/
+ https://www.west-wind.com/
+ https://zimmergren.net/
