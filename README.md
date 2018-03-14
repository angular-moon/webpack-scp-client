# webpack-sftp-client

## Introduction

A plugin for webpack as an sftp client, forked from sqhtiamo/webpack-sftp-client

## Installation

```
npm install webpack-sftp-client
```

## Usage

```
const WebpackSftpClient = require('webpack-sftp-client');

new WebpackSftpClient({
    port: '22',
    host: 'exmaple.com',
    username: 'root',
    password: 'password',
    path: './build/',
    remotePath: '/data/website/demo/',
    // Show details of uploading for files
    verbose: true
})
```

licenses MIT
