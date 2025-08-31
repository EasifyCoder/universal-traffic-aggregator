# universal-traffic-aggregator

[English](./README-en.md) | 简体中文

# Important Notice

1. This project includes comprehensive documentation and detailed video tutorials from setup to development to deployment

2. This project requires you to have some basic knowledge of Golang and Vue

3. You can completely complete all operations through our tutorials and documentation, therefore we no longer provide free technical services. If you need services, please [pay for support]()

4. If you use this project for commercial purposes, please comply with the Apache 2.0 license and retain the author's technical support statement. You need to retain the following copyright declaration information, as well as the copyright declaration information contained in logs and code. All required retained information is textual in nature and will not affect any business content. If you decide to use it commercially [commercial activities that generate revenue are all considered commercial use] or must remove it, please [purchase authorization]()

## 1. Basic Introduction

### 1.1 Project Introduction

> universal-traffic-aggregator (UTA) is a full-stack front-end and back-end separated "Market Promotion - Business Conversion Integration Platform" developed based on [Vue](https://vuejs.org) and [Gin](https://gin-gonic.com). It integrates article publishing, posting, materials, knowledge payment courses, Todo tasks, membership system settings, and payment integration. The project will continue to be updated (e-commerce module, PDF module, education and training module coming soon), allowing you to focus more time on business expansion.

[Online Preview](https://www.yhyk.fun/yhyk/): https://www.yhyk.fun/yhyk/

Test Username: 19102060001

Test Password: 19102060001Aa

### 1.2 Contribution Guidelines

Hi! First of all, thank you for your interest in universal-traffic-aggregator.

universal-traffic-aggregator is a complete set of front-end and back-end separated architecture-style market promotion-business conversion integration platform prepared for quickly承接公域流量, providing professional articles, posting, materials, knowledge payment products and other general social functions.

The growth of universal-traffic-aggregator cannot be separated from everyone's support. If you are willing to provide suggestions for universal-traffic-aggregator, please read the following content.

#### 1.2.1 Issue Standards
- Issues are only used to submit Bug or Feature related content, as well as design-related content. Other content may be directly closed.
									      
- Before submitting an issue, please search whether the related content has already been proposed.

#### 1.2.2 Pull Request Standards
- Please first fork a copy to your own project, do not create branches directly under the repository.

- Commit information should be filled in the form of `[filename]: description`, for example `README.md: fix xxx bug`.

- If it's a bug fix, please provide description information in the PR.

- Code merging requires the participation of two maintainers: one person reviews and approves, and another person reviews again. After passing, it can be merged.

## 2. Usage Instructions

### 2.1 Server Project

Use `Goland` and other editing tools to open the server directory, do not open the gin-vue-admin root directory

```bash

# Clone the project
git clone https://github.com/EasifyCoder/universal-traffic-aggregator.git
# Enter the server folder
cd server

# Use go mod and install go dependency packages
go generate

# Run
go run . 

```

### 2.2 Web Project

```bash
# Enter the web folder
cd web

# Install dependencies
npm install

# Start the web project
npm run serve
```

### 2.3 Swagger Automated API Documentation

#### 2.3.1 Install swagger

``` shell
go install github.com/swaggo/swag/cmd/swag@latest
```

#### 2.3.2 Generate API Documentation

```` shell
cd server
swag init
````

## 3. Technology Selection

- Frontend: Built basic pages using [Element](https://github.com/ElemeFE/element) based on [Vue](https://vuejs.org).
- Backend: Quickly built basic RESTful-style APIs using [Gin](https://gin-gonic.com/), [Gin](https://gin-gonic.com/) is a web framework written in Go language.
- Database: Uses `MySQL` > (5.7) version with InnoDB database engine, and uses [GORM](http://gorm.cn) to implement basic database operations.
- API Documentation: Uses `Swagger` to build automated documentation.
- Configuration Files: Uses [Viper](https://github.com/spf13/viper) to implement `YAML` format configuration files.
- Logging: Uses [Zap](https://github.com/uber-go/zap) to implement log recording.

## 4. Project Architecture

### 4.1 System Architecture Diagram

### 4.2 Directory Structure

## 5. Main Features

The UTA project includes complete frontend, backend, and operation backend. The main feature introduction is mainly based on the frontend page display functions. All functions can be configured in the operation backend.

- Article Reading: The backend can set article categories, and articles can be written and published based on categories. Users can like, favorite, comment and other operations on articles.
- Posting: After logging in, users can freely post. Each post contains text and images, and users can choose to publish under the corresponding post category.
- Membership: Complete membership system and points system to enhance user stickiness.
- Materials: Materials can be set as free materials and paid materials. Supports advanced functions such as member pricing, member free, member exclusive, etc.
- Graphic Courses: Can be set as free courses and paid courses. Supports advanced functions such as member pricing, member free, member exclusive, etc. Perfect carrier for承接知识付费体验课, training camps, and accompaniment camps.
- Tool Navigation: Provides quick navigation for commonly used tools and websites, including development tools, design tools, learning resources and other categorized organization, making it convenient for users to quickly find the tools they need.
- Todo: Personal task management system, supports creating, editing, and deleting todo items, setting priorities and deadlines, helping users efficiently manage daily tasks.
- Daily News: Aggregates daily important news and industry dynamics, provides concise news summaries and in-depth analysis, allowing users to quickly understand the latest information and trends.

## 6. Contact Information

| WeChat |
|  :---:  | 
| <img width="150" src="./assets/宇皓AI.png"> 


## 7. Donation

If you feel this project has helped you, you can buy the author a drink :tropical_drink:

## 8. Important Notes

Please strictly comply with the Apache 2.0 license and retain the work declaration. Removing copyright information must obtain authorization. Unauthorized removal of copyright information will be legally pursued according to the law. 