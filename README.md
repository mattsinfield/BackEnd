this is the start of a file

# EmplManagerBackEnd

A simple NodeJS backend service for retrieving employees by position wihtin the company.

## Setup

The project requires npm and NodeJS to be installed.

### Build Project

1. Install typescript: `npm install -g typescript`
2. Install npx: `npm install npx`
3. Install project dependencies: `npm install`

## Launch Server

1. `npx ts-node src/Server.tx`
2. Check localhost ap aport [8080](http://localhost:8080/)

## Services

| Position | URL |
| -------- | --- |
| All Employees   | http://localhost:8080/allemployees |
| Juniors   | http://localhost:8080/juniors |
| Programmers   | http://localhost:8080/programmers |
| Engineers   | http://localhost:8080/engineers |
| Experts   | http://localhost:8080/experts |
| Managers   | http://localhost:8080/managers |
| Admins   | http://localhost:8080/admins |
| Non Admins   | http://localhost:8080/nonadmins |