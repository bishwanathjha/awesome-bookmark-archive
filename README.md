# awesome-bookmark-archive
A curated collection of my personal tech bookmarks, offering a stable repository for valuable links rarely updated. This is an effort to cleanup my personal notes and put things together at one place so that it might help someone. 

`Please Note:` _I do not actively maintain these information, so it's very likely that some of the information might be outdated or not relevant._

## Languages & Frameworks
### Golang
- <a href="https://awesome-go.com/" target="_blank">Awesome-go.com</a>
- <a href="https://github.com/avelino/awesome-go/" target="_blank">https://github.com/avelino/awesome-go</a>
- <a href="https://codesahara.com/blog/how-to-deploy-golang-to-production-step-by-step/" target="_blank">how-to-deploy-golang-to-production-step-by-step</a>
- Some links realted to Go project directory structure
    - <a href="https://github.com/golang-standards/project-layout" target="_blank">project-layout</a>
    - <a href="https://peter.bourgon.org/go-best-practices-2016/#repository-structure" target="_blank">repository-structure</a>
    - <a href="https://xeiaso.net/blog/within-go-repo-layout-2020-09-07/" target="_blank">within-go-repo-layout</a>
    - <a href="https://tutorialedge.net/golang/go-project-structure-best-practices/" target="_blank">go-project-structure-best-practices</a>

### PHP
- <a href="https://phptherightway.com/" target="_blank">https://phptherightway.com/</a>
- <a href="https://www.php-fig.org/" target="_blank">https://www.php-fig.org/</a>
- <a href="https://github.com/DesignPatternsPHP/DesignPatternsPHP" target="_blank">DesignPatternsPHP</a>
- <a href="https://github.com/ziadoz/awesome-php" target="_blank">awesome-php</a>
- <a href="https://thephpleague.com/" target="_blank">https://thephpleague.com/</a>
- <a href="http://phpsadness.com" target="_blank">Fun topic about php</a>

## Security
- Cross Site Scripting Prevention Cheat Sheet
    - <a href="https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html" target="_blank">Cross_Site_Scripting_Prevention_Cheat_Sheet</a>
    - <a href="https://www.acunetix.com/websitesecurity/cross-site-scripting/" target="_blank">cross-site-scripting</a>
    - <a href="https://cheatsheetseries.owasp.org/cheatsheets/XSS_Filter_Evasion_Cheat_Sheet.html" target="_blank">S_Filter_Evasion_Cheat_Sheet</a>    

## Docker
https://github.com/docker/awesome-compose


## AWS

- <a href="https://states-language.net/spec.html#example" target="_blank">Amazon States Language</a>
- <a href="https://dashbird.io/blog/ultimate-guide-aws-step-functions/" target="_blank">The Ultimate Guide to AWS Step Functions</a>
- <a href="https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_Tutorials.WebServerDB.CreateWebServer.html" target="_blank">Install a web server on your EC2 instance</a>

### AWS Lambda
- <a href="https://docs.aws.amazon.com/pdfs/lambda/latest/dg/lambda-dg.pdf" target="_blank">Amazon Lambda</a>

## Microservices
- <a href="https://microservices.io/index.html" target="_blank">https://microservices.io</a>
- <a href="https://www.youtube.com/watch?v=heh4OeB9A-c&ab_channel=GoogleTalksArchive" target="_blank">How To Design A Good API and Why it Matters</a>

## Data structure and algorithms
The following are some common data
structures that tend to come up often in questions. If you
haven’t used them in a while, practice beforehand. You should
be familiar with when to use each one and their pros and cons.
You will need to explain the complexity of your
algorithm (big O).

    Arrays and Strings
    Queues and Lists
    Linked Lists
    Trees / Tries
    Hash maps / Hash sets
    Graphs

- <a href="https://leetcode.com/problemset/" target="_blank">Leetcode problems all</a>
- <a href="https://visualgo.net/en" target="_blank">visualising data structures and algorithms through animation</a>
- <a href="https://leetcode.com/problemset/" target="_blank">projecteuler problems archives</a>
- <a href="https://www.codechef.com/cptutorials/" target="_blank">https://www.codechef.com/cptutorial</a>
- <a href="https://github.com/mission-peace/interview/wiki" target="_blank">https://github.com/mission-peace/interview/wiki</a>
- <a href="https://app.codility.com/demo/take-sample-test/" target="_blank">https://app.codility.com/demo/take-sample-test</a>
- <a href="https://github.com/Algorithm-archive/Learn-Data_Structure-Algorithm-by-PHP" target="_blank">https://github.com/Algorithm-archive/Learn-Data_Structure-Algorithm-by-PHP</a>
- <a href="https://www.geeksforgeeks.org/must-do-coding-questions-for-companies-like-amazon-microsoft-adobe/" target="_blank">https://www.geeksforgeeks.org/must-do-coding-questions-for-companies-like-amazon-microsoft-adobe/</a>
- <a href="https://www.geeksforgeeks.org/experienced-interview-experiences-company-wise/" target="_blank">https://www.geeksforgeeks.org/experienced-interview-experiences-company-wise/</a>

### Google specific
- <a href="https://www.interviewbit.com/google-interview-questions/" target="_blank">https://www.interviewbit.com/google-interview-questions/</a>
- <a href="https://techdevguide.withgoogle.com/paths/data-structures-and-algorithms/" target="_blank">https://techdevguide.withgoogle.com/paths/data-structures-and-algorithms/</a>
- <a href="https://techdevguide.withgoogle.com/paths/interview/" target="_blank">https://techdevguide.withgoogle.com/paths/interview/</a>
- <a href="https://techdevguide.withgoogle.com/resources/topics/made-by-google/?no-filter=true#!" target="_blank">https://techdevguide.withgoogle.com/resources/topics/made-by-google/?no-filter=true#!</a>
- <a href="https://levelup.gitconnected.com/my-google-interview-experience-33dc45e1a671" target="_blank">https://levelup.gitconnected.com/my-google-interview-experience-33dc45e1a671</a>


## Linux

-  SSH to the server
    ```
    ssh -i abc.pem ec2-user@xx.xx.x.xxxx
    ```

-  SCP zip file to remote server
    ```
    scp file.zip -i test.pem bitnami@ec2-xx-xx-xx-x.ap-south-1.compute.amazonaws.com:~/
    ```

- Know the runtime based on pid
    ```
    ps -eo pid,lstart,etime | grep 10176
    ```

- Find larger files on the machine sorted
    ```
    find  /var/www/html/* -type f -printf "%S\t%p\n" | sort -nr | head -10

    ```    
- Compress the pdf file using Ghost Script
https://gist.github.com/guifromrio/6390547
    ```
    gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/ebook -dNOPAUSE -dPDFSTOPONERROR -sOutputFile=8ebab172800656df73f7cb444a0e74e5dc98a64a 8ebab172800656df73f7cb444a0e74e5dc98a64a
    ```    
## Database

- Get MySQL database size
    ```
    SELECT  
        table_schema as db,
        table_name AS tab,
        round(((data_length + index_length) / 1024 / 1024), 2) as size_mb  
    FROM information_schema.TABLES
    where table_schema = "your-database-name" 
    ORDER BY (data_length + index_length) DESC;
    ```


## Few liked articles & blogs
- <a href="https://blog.thea.codes/opinions-after-a-decade/" target="_blank">https://blog.thea.codes/opinions-after-a-decade/</a>
- <a href="https://www.juststeveking.uk/blog/two-developers-approach-the-same-problem" target="_blank">two-developers-approach-the-same-problem/</a>
- <a href="https://leetcode.com/problemset/" target="_blank">Leetcode problems all</a>




