# PHP Restful API Starter Kit - Database Scripts

A starter kit for the restful API database scripts. These database scripts support the PHP Restful API Starter Kit project found at: https://github.com/crmcmullen/medium-php-api-starter

New articles in the future will be features built upon this foundation.

This code accompanies my Medium article entitled, "How to Build a Simple Restful API in PHP" 
located at: https://medium.com/better-programming/how-to-build-a-simple-restful-api-in-php-c719f03cfa0a

## License ##
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## The Sample Code

All of the sample code is available in the following three GitHub repositories. Feel free to download and use this code any way you want, without attribution:

    Back-end API: https://github.com/vuchkov/medium-php-api-starter
    Client-side front end: https://github.com/vuchkov/medium-php-api-starter-client
    Database scripts: https://github.com/vuchkov/medium-php-api-starter-dbscripts

I obviously built this project on my localhost with the back-end API in one project and the client-side front end in a separate project. To make this simple demonstration work, there are some hardcoded references (e.g., database connection details, API host URL, etc). I’ll come back in a later article, and we’ll refine our project by moving these things into INI files and database tables so we don’t have those things in our code. But for now, the idea is to just keep it simple.

I decided on separate repositories for everything because I do intend to come back and build on this project in later articles. The master branch in each repository will always be the most current version of the code, but I’ll leave each feature branch in the repository so you can roll back at any time and work with the application at any stage. That being said, each of these repositories contain a branch called original which will be the code we work with here as a starting point.

As a side note, my development environment is set up entirely in Docker containers using the instructions you can find in my recent article, “How to Run Your Entire Development Environment in Docker Containers on macOS: https://betterprogramming.pub/php-how-to-run-your-entire-development-environment-in-docker-containers-on-macos-787784e94f9a.

## Resource

- Betterprogramming.pub, 2020: https://betterprogramming.pub/how-to-build-a-simple-restful-api-in-php-c719f03cfa0a
