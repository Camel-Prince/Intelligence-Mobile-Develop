# Flutter-Introduction
## What is Flutter?
`Flutter is Google’s UI toolkit for building beautiful, natively compiled applications for mobile, web, and desktop from a single codebase.`
## Why Flutter?
- **Fast Development!** Paint your app to life in milliseconds with Stateful Hot Reload. Use a rich set of fully-customizable widgets to build native interfaces in minutes.
![Fast-Dev](./flutter_markdown_source/fast.png)
- **Expressive and Flexible UI!** Quickly ship features with a focus on native end-user experiences. Layered architecture allows for full customization, which results in incredibly fast rendering and expressive and flexible designs.
![Flexible_UI](./flutter_markdown_source/beautilful.png)
- **Native Performance!** Flutter’s widgets incorporate all critical platform differences such as scrolling, navigation, icons and fonts, and your Flutter code is compiled to native ARM machine code using [Dart's native compilers](https://dart.dev/platforms).
![native-performance](flutter_markdown_source/native.png)


## Who is using Flutter?
Organizations ***around the world*** are building apps with Flutter.
![who's using](flutter_markdown_source/who.png)
[See what's being created](https://flutter.dev/showcase)

#### [click here for more about Flutter](https://flutter.dev/) 

- ***Tips***
I came to  git-push failure during my first try(which throws: `LibreSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443`)
I solved by using the command:
`networksetup -setv6off Wi-Fi` which means to resolve the hosts name by Ipv4 insdead of Ipv6. And `networksetup -setv6automatic Wi-Fi` can turn the Ipv6 on again.