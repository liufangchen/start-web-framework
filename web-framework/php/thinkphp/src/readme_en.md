# ThinkPHP case

<toc>

<p align="center"><b> <a href="./readme.md"> 中文 </a> | English </b></p>

- [Quick start](#Quick-start)
    - [Deploy via command line tool](#Deploy-via-command-line-tools)
- [Application details](#Application-details)
- [About Us](#About-Us)

</toc>

# Quick start

- [:octocat: source](https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/thinkphp/src)
- [:earth_africa: Effect Preview](http://thinkphp.web-framework.1583208943291465.cn-shenzhen.fc.devsapp.net/)

## Deploy via command line tools

> Before starting, you need to install the Serverless Devs developer tools: `npm install @serverless-devs/s -g`, for more installation methods, please refer to [Serverless Devs Installation Documentation](https://www.serverless-devs.com/serverless-devs/install) , you also need to configure key information for Alibaba Cloud. For the method of configuring key information, please refer to [Alibaba Cloud Key Configuration Document](https://www.serverless-devs.com/fc/config)
- Initialize the project: `s init start-thinkphp -d start-thinkphp`
    > It involves determining the selection of the key, the determination of the service name, the determination of the function name, and the determination of the container image
- Enter the project: `cd start-thinkphp`
- Deploy the project: `s deploy -y`
- Invoke： According to the returned `url` information, you can make a request in the browser

# Application details
This project is to deploy very popular development framework ThinkPHP to Aliyun Serverless platform (Function Compute FC).

By Serverless Devs developer tools, you only need a few steps to experience the technical bonus of reducing costs and improving efficiency brought by Serverless architecture.

After the deployment is complete, you can see the case address returned to you by the system, for example:

![Picture alt](https://img.alicdn.com/imgextra/i1/O1CN01erNjW520M1S3N5XbG_!!6000000006834-2-tps-2498-932.png)

At this time, open the case address and you can enter the home page of the ThinkPHP:

![Picture alt](https://img.alicdn.com/imgextra/i2/O1CN012pLm1A1HIDS3XgnPf_!!6000000000734-2-tps-1660-882.png)


# About Us
- Serverless Devs Tools:
    - Repository: [https://www.github.com/serverless-devs/serverless-devs](https://www.github.com/serverless-devs/serverless-devs)
      > Welcome to add a :star2:
    - Official website: [https://www.serverless-devs.com/](https://www.serverless-devs.com/)
- Alibaba Cloud Function Compute components:
    - Repository: [https://github.com/devsapp/fc](https://github.com/devsapp/fc)
    - Help document: [https://www.serverless-devs.com/fc/readme](https://www.serverless-devs.com/fc/readme)
- Dingding communication group: 33947367