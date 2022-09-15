# Form Applcation

Form Applcation is a system that allows users creating predefined multiple form fileds as many as they wish.

<!-- ## Live Version

A live version of this application can be found at
[https://timesheet-io.herokuapp.com](https://timesheet-io.herokuapp.com) -->

### Features

- User Authentication with Devise.
- New Form creations
- New Contract creations
- Fill Form from other users (via QR or link)
- Manage Form
- Database with MongoDB.

### Tech

* [Ruby on Rails] 
* [ReactJS]
* [Bootstrap Ui]
* [MongoDB]

## Running Locally

The application requires Ruby on Rails 6, NodeJs and MongoDB to run.
In order to run this locally, the following is required:

+ Ruby (version 2.6.9)
+ Rails (version 6.1.4)
+ MongoDB (version 6)

Running on Backend

```sh
$ cd fmBackend
$ bundle install
$ rails s
```

Running on Frontend
```sh
$ cd fmfrontend
$ npm install
$ npm run start
```

Running MongoDB
$ xcode-select --install
$ brew tap mongodb/brew
$ brew update
$ brew install mongodb-community@6.0
$ brew services start mongodb-community@6.0

### Future Todos

 - Dynamic Form.
 - Drag | Drop lable to group.
 - MVC Form
