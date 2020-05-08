---
title: Sample integration between react-native and a gRPC service
date: 2018-01-25
tags: ['project', 'javascript', 'grpx' ,'react-native']
---

A sample react-native app that communicates using gRPC with a sample server, also contained in this repo. Both the client app and the server share the protocol buffer definition, which is used to generate both server and client side code.

The client side react-native application can talk to the gRPC server through a native module that bridges react-native and the objective-c/Java client generated by gRPC tooling.

[![danijg/react-native-grpc - GitHub](https://gh-card.dev/repos/danijg/react-native-grpc.svg?fullname=)](https://github.com/danijg/react-native-grpc)