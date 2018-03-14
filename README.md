# webpack-sftp-client

## Introduction

A plugin for webpack as an scp client

## Installation

```
npm install --save-dev @angular-moon/webpack-scp-client

or

yarn add -D @angular-moon/webpack-scp-client

```

## Usage

```
const WebpackSftpClient = require('@angular-moon/webpack-scp-client');

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
