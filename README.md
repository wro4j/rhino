Rhino
=====
Rhino is an open-source implementation of JavaScript written entirely in Java

This project is an unofficial rhino distribution required by wro4j. If you think that your project can benefit from using it, feel free to use it as well. 

Since there wasn't any release for a long time, I decided to perform a release from the latest master branch. The released version has no patch applied and uses original sources as is. This project is useful until an official rhino release is available.

I've tested it with a large suite of tests (in wro4j-extensions module) and everything seems to work fine. If you have any issues, please open an issue or just let me know.


Usage
=====
Include the following dependency to pom.xml:

    <dependency>
        <groupId>ro.isdc.wro4j</groupId>
        <artifactId>rhino</artifactId>    
        <version>1.7R5-20130223</version>
    </dependency> 
    
Notice that the groupId is not the same as official one and the version uses the following convention:

    ${rhino.version}-${timestamp}

where ${rhino.version} - is the unofficial version of rhino (1.7R5)
and ${timestamp} - the timestamp of the last commit from master branch (a kind of snapshot) from where the release was performed.