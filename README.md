# StackOverflow Clone

A feature-rich Q&A platform built with ASP.NET Core 6 MVC, implementing core StackOverflow functionality with modern architecture patterns.

## Features

- **User Authentication**: Secure registration, login with role-based access control
- **Question Management**: Create, edit, delete questions with rich text support
- **Answer System**: Post answers, mark accepted answers, edit/delete functionality
- **Voting System**: Upvote/downvote questions and answers
- **Tagging**: Organize questions with tags for better discoverability
- **User Profiles**: Track user questions, answers, and reputation
- **Search & Filter**: Find questions by tags, pagination support
- **Responsive Design**: Mobile-friendly interface with Bootstrap 5

## Technology Stack

- **Framework**: ASP.NET Core 6.0 MVC with Razor Pages
- **Database**: MS SQL Server with NHibernate ORM
- **Authentication**: ASP.NET Core Identity with NHibernate integration
- **Architecture**: Three-tier: Web, Application, Infrastructure
- **DI Container**: Autofac
- **Logging**: Log4Net
- **Frontend**: Razor Views, Bootstrap 5, jQuery
- **Markdown**: Markdig for rich text formatting
- **Security**: HtmlSanitizer for XSS protection

## Prerequisites

- .NET 6.0 SDK or higher
- MS SQL Server (Express or higher)


## Default User Accounts

### Admin Account
- **Email**: sadmin@gmail.com
- **Password**: 123456
- **Role**: Admin (manage tags, moderate content)

### Regular User
- **Email**: abc@gmail.com
- **Password**: 123456
- **Role**: User (ask questions, post answers, vote)