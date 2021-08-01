# Awesome .NET Core

# Contents
+ General
+ Interview
+ Frameworks, Libraries and Tools
+ References

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

# References
+ https://github.com/thangchung/awesome-dotnet-core
+ https://github.com/thangchung/awesome-dotnet
+ https://github.com/quozd/awesome-dotnet
+ https://awesomerank.github.io/lists/thangchung/awesome-dotnet-core.html

# History
+ Thời kỳ tiền sử
+ Thời kỳ cổ đại (2879–111 TCN)
+ Thời kỳ Bắc thuộc (179 TCN–938)
+ Thời kỳ quân chủ (939–1945)
+ Thời kỳ hiện đại (1858–nay)
  + Thời kỳ Pháp thuộc (1858–1945)
  + Thời kỳ Nhật thuộc (1940–1945)
  + Thời kỳ cộng hòa (1945–nay)
    + Ngày 2 tháng 9 năm 1945 tại Hà Nội, Hồ Chí Minh tuyên bố thành lập nước Việt Nam Dân chủ Cộng hòa độc lập và thống nhất từ miền Bắc tới miền Nam. Đầu năm 1946, một cuộc bầu cử toàn quốc đã được tổ chức. Các đại biểu Việt Minh chiếm ưu thế, song các phe phái khác cũng tham gia chính phủ. Quốc kỳ được chọn là cờ nền đỏ, sao vàng năm cánh, hiến pháp được thông qua. Nhà nước Việt Nam Dân chủ Cộng hòa chính thức trở thành người đại diện hợp pháp của nhân dân Việt Nam từ Bắc chí Nam.
    + Chiến tranh Đông Dương (1946–1954)
      + Năm 1950, chính quyền Cộng hòa Nhân dân Trung Hoa và Liên Xô bắt đầu viện trợ vũ khí cho Việt Nam Dân chủ Cộng hòa. Bên kia, Pháp được Mỹ hậu thuẫn, hỗ trợ phần lớn chiến phí, nhưng đầu thập niên 1950, thế trận của Pháp ngày càng yếu đi ở Đông Dương.
      + Thất bại ở trận Điện Biên Phủ vào tháng 5 năm 1954 đã kết thúc hoàn toàn nỗ lực của Pháp và Mỹ nhằm chiếm giữ Việt Nam và toàn bộ Đông Dương.
    + Chiến tranh Việt Nam (1955–1975)
      + Hoa Kỳ quyết định hậu thuẫn cho Ngô Đình Diệm thành lập chính phủ ở phía Nam vĩ tuyến 17.
      + Năm 1955, với sự trợ giúp của Mỹ, Ngô Đình Diệm đã gian lận để chiến thắng trong Cuộc trưng cầu dân ý miền Nam Việt Nam, cho phép ông phế truất Bảo Đại, lên làm Quốc trưởng của Quốc gia Việt Nam và sau này trở thành Tổng thống của chính phủ Việt Nam Cộng hòa.
      + Tướng lĩnh Quân lực Việt Nam Cộng hòa đảo chính và ám sát Ngô Đình Diệm ngày 1 tháng 11 năm 1963, chấm dứt nền Đệ Nhất Cộng hòa và thành lập nền Đệ Nhị Cộng hòa. 
      + Sau giai đoạn đảo chính liên tiếp, năm 1967, Nguyễn Văn Thiệu lên làm Tổng thống nền Đệ nhị Cộng hòa của Việt Nam Cộng hòa. Ở miền Bắc, Lê Duẩn là lãnh đạo của Việt Nam Dân chủ Cộng hòa sau khi Chủ tịch Hồ Chí Minh qua đời vào năm 1969.
      + Tháng 1 năm 1974, Trung Quốc đã tấn công vào quần đảo Hoàng Sa lúc đó đang do Quân lực Việt Nam Cộng hòa kiểm soát và chiếm đóng hoàn toàn quần đảo này.
    + Thời kỳ đầu sau thống nhất (1976–1986)
      + Ngày 30 tháng 4 năm 1975, Quân Giải phóng miền Nam Việt Nam giành được quyền kiểm soát Sài Gòn, Tổng thống Dương Văn Minh của Việt Nam Cộng hòa tuyên bố đầu hàng Chính phủ Cách mạng lâm thời Cộng hòa miền Nam Việt Nam.
      + Ngày 25 tháng 4 năm 1976, Việt Nam Dân chủ Cộng hòa và Cộng hòa miền Nam Việt Nam tổ chức Tổng tuyển cử để thống nhất về mặt nhà nước thành một quốc gia có tên chính thức là Cộng hòa Xã hội chủ nghĩa Việt Nam. Năm 1977, Việt Nam trở thành thành viên của Liên Hợp Quốc.
      + Vào tháng 12 năm 1978, quân Khmer Đỏ mở các cuộc tấn công lớn vào các tỉnh biên giới từ Tây Ninh đến Kiên Giang, thị xã Hà Tiên bị chiếm.
      + Ngày 17 tháng 2 năm 1979, với lực lượng khoảng 400.000 quân, Trung Quốc đã bất ngờ tấn công vào các tỉnh biên giới phía Bắc của Việt Nam từ Quảng Ninh tới Lai Châu, sau 3 tuần đã chiếm được thủ phủ các tỉnh này.
      + Tới ngày 18 tháng 3 năm 1979, Trung Quốc tuyên bố rút quân khỏi những vùng biên giới mà họ đánh chiếm được.
      + Tháng 3 năm 1988, Trung Quốc sử dụng tàu chiến để tấn công các tàu công binh của phía Việt Nam, mở cuộc hải chiến vào các bãi đá Cô Lin, Len Đao, Gạc Ma thuộc quần đảo Trường Sa và chiếm đóng Gạc Ma, phía Việt Nam bảo vệ được bãi Cô Lin và Len Đao thành công.
      + Năm 1992, hai nước Việt Nam và Trung Quốc mới bình thường hóa lại quan hệ ngoại giao.
    + Thời kỳ đổi mới (1986–nay)
      + Năm 1986, Đại hội Đảng Cộng sản Việt Nam: cải cách kinh tế theo hướng kinh tế thị trường với định hướng Xã hội chủ nghĩa.
      + Từ 1991–1995, nhịp độ tăng bình quân hàng năm về tổng sản phẩm trong nước (GDP) đạt 8,2%.
      + Năm 2004, Việt Nam đã đạt được mức tăng trưởng là 7,7%.
      + Năm 2005, tăng trưởng GDP của Việt Nam là 8,5%.
      + Đến nay, Việt Nam đã thiết lập quan hệ ngoại giao với 167 nước, có quan hệ buôn bán với trên 100 nước. Các công ty của hơn 70 nước và vùng lãnh thổ đã đầu tư trực tiếp vào Việt Nam.
      + Năm 1995, Việt Nam đã bình thường hóa quan hệ với Mỹ, và tiếp đó gia nhập ASEAN, APEC, thành viên diễn đàn ASEM.
      + Ngày 11 tháng 1 năm 2007, Việt Nam chính thức trở thành thành viên thứ 150 của Tổ chức Thương mại Thế giới (WTO) sau 11 năm đàm phán.
      + Ngày 16 tháng 10 năm 2007, Việt Nam đã được bầu làm một trong các thành viên không thường trực của Hội đồng Bảo an Liên Hợp Quốc nhiệm kỳ 2008–2009.
      + Năm 2008: Cuộc khủng hoảng tài chính toàn cầu.
      + Các sự kiện tranh chấp ở biển Đông như:
        + Tàu địa chấn Bình Minh 02 bị hải giám Trung Quốc cắt cáp.
        + Vụ giàn khoan Hải Dương 981.
        + Việc Trung Quốc xây đảo nhân tạo ở biển Đông.
      + Việc hình thành **Cộng đồng Kinh tế ASEAN** và hợp tác toàn diện với Hoa Kỳ, ký các **Hiệp định thương mại tự do** với **Nhật Bản**, **Hàn Quốc** và **Liên minh châu Âu**.
      + **Hiệp hội các Quốc gia Đông Nam Á** (tiếng Anh: Association of South East Asian Nations, viết tắt là ASEAN) là một tổ chức chính trị, kinh tế, văn hóa và xã hội của các quốc gia trong khu vực Đông Nam Á. Tổ chức này được thành lập ngày 8 tháng 8 năm 1967 với các thành viên đầu tiên là Thái Lan, Indonesia, Malaysia, Singapore và Philippines, nhằm biểu hiện tinh thần đoàn kết giữa các nước trong cùng khu vực với nhau, đồng thời hợp tác chống tình trạng bạo động và bất ổn tại những nước thành viên.
      + **Cộng đồng kinh tế ASEAN** (tiếng Anh: ASEAN Economic Community, viết tắt: AEC) là một khối kinh tế khu vực của 10 quốc gia thành viên ASEAN chính thức được thành lập vào ngày 31 tháng 12 năm 2015, khi bản tuyên bố thành lập chính thức có hiệu lực.
      + Ngày 31 tháng 12 năm 2015 là ngày thành lập Cộng đồng Kinh tế ASEAN – ASEAN Economic Community, viết tắt AEC, gồm 10 quốc gia thành viên. **AEC** sẽ là cơ hội quý báu để Việt Nam đẩy mạnh xuất khẩu, thu hút đầu tư nước ngoài, nhanh chóng bắt nhịp với xu thế và trình độ phát triển kinh tế của khu vực và thế giới.
      + Trong bối cảnh ASEAN nhảy vọt từ nấc **Khu vực Mậu dịch Tự do ASEAN (AFTA)** lên nấc thang **Cộng đồng Kinh tế (AEC)**. Hiện nay, trình độ phát triển của Việt Nam còn kém xa nhiều quốc gia trong ASEAN như: Singapore, Malaysia, Thái Lan,... Do vậy, sức ép cải cách đặt ra với Việt Nam là rất lớn.
      + Xếp hạng năng lực cạnh tranh quốc gia của Việt Nam do **Diễn đàn Kinh tế Thế giới (WEF)** công bố cho năm **2015–2016**, Việt Nam đứng rất thấp trong khu vực và chỉ đứng thứ 56 trên tổng số 144 nền kinh tế. Nền quản lý hành chính lạc hậu, nhiều thủ tục rườm rà gây ảnh hưởng tiêu cực nghiêm trọng đến năng lực cạnh tranh, chi phí về thời gian và tiền bạc của doanh nghiệp Việt Nam, đơn cử như việc các doanh nghiệp Việt Nam cần đến 872 giờ/năm để đóng thuế trong khi con số bình quân của dịch vụ đó ở các nước ASEAN-6 chỉ là 172 giờ/năm. Thực tế này cho thấy, cải cách thể chế, tái cơ cấu kinh tế, **nâng cao trình độ khoa học – công nghệ** và năng lực cạnh tranh đang là đòi hỏi cấp thiết đặt ra cho Việt Nam trong giai đoạn tới.
      + Tính đến năm 2020, Việt Nam đã thiết lập quan hệ ngoại giao với 189 quốc gia và là thành viên của nhiều tổ chức quốc tế, trong đó nổi bật như: **Liên Hợp Quốc**, **Hiệp hội các quốc gia Đông Nam Á (ASEAN)**, **Diễn đàn Hợp tác Kinh tế Châu Á – Thái Bình Dương (APEC)** và **Tổ chức Thương mại Thế giới (WTO)**.
+ Triều Nguyễn – triều đại Phong kiến cuối cùng ở Việt Nam, đã tồn tại trong suốt hơn 143 năm (1802-1945) với 13 đời vua Nguyễn, 9 chúa Nguyễn
+ Vua Gia Long (1802-1819)*
  + Ngày 1-2-1802, Nguyễn Phúc Ánh lên ngôi Hoàng đế ở Phú Xuân, lấy niên hiệu là Gia Long, chính thức lập nên triều đại nhà Nguyễn. Tháng 3 năm 1804, vua Gia Long đổi quốc hiệu nước ta là Việt Nam.
+ Vua Minh Mạng (1820-1840)
  + Cho bỏ các dinh và trấn mà thành lập các tỉnh (cả nước được chia làm 31 tỉnh)
  + Nhà vua cho lập Quốc Tử Giám, mở thêm kỳ thi Hội và thi Đình (thời Gia Long chỉ có thi Hương).
  + Lãnh thổ Việt Nam dưới thời Minh Mạng được mở rộng nhất trong lịch sử và Việt Nam thực sự trở thành một quốc gia hùng mạnh. Vì vậy vào năm 1838, vua Minh Mạng cho đổi tên nước ta là Đại Nam.
+ Vua Thiệu Trị (1841-1847)
+ Vua Tự Đức (1848-1883)
  + Vua Tự Đức không con, ông nhận 3 người cháu gọi bằng chú làm con nuôi là: Nguyễn Phúc Ưng Chân (sau này là vua Dục Đức); Nguyễn Phúc Ưng Đường (sau này là vua Đồng Khánh); Nguyễn Phúc Ưng Đăng (sau này là vua Kiến Phúc).
+ Vua Dục Đức (1883, 3 ngày)
+ Vua Hiệp Hòa (1883, 4 tháng)
+ Vua Kiến Phúc (1883-1884)
+ Vua Hàm Nghi (1884-1885)*
  + Binh biến năm Ất Dậu (5-7-1885) xảy ra, vua Hàm Nghi cùng quần thần ra Tân Sở, phát hịch Cần Vương, phát động phong trào kháng Pháp trên toàn quốc.
+ Vua Đồng Khánh (1886-1888)
+ Vua Thành Thái (1889-1907)
  + Vua Thành Thái là người có tư tưởng tiến bộ (cắt tóc ngắn, lái ô tô, xuồng máy) và có tư tưởng chống Pháp.
+ Vua Duy Tân (1907-1916)
  + Vua Duy Tân là vị vua lên ngôi nhỏ tuổi nhất trong 13 vua Nguyễn.
+ Vua Khải Định (1916-1925)
  + Vua Khải Định chỉ có một con trai là Hoàng tử Vĩnh Thụy (vua Bảo Đại).
+ Vua Bảo Đại (1926-1945)
  + Vua Bảo Đại ở ngôi cho đến 30 tháng 8 năm 1945 thì làm lễ thoái vị tại Ngọ Môn, giao chính quyền lại cho Chính phủ Cách mạng Lâm thời.
  + Chế độ phong kiến chấm dứt, Bảo Đại sang Pháp và sống hết cuộc đời của vị vua lưu vong ở đó. Ông mất ngày 1 tháng 8 năm 1997 tại Pháp.
Vua Bảo Đại có 5 người con (2 trai, 3 gái).
