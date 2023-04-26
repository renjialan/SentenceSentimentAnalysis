Instructions on how to use this: 

1. Before you can start using Stanford CoreNLP, you need to do the following setup:

To run Stanford CoreNLP, you need Java 1.8 or later.
Download the Stanford CoreNLP package (https://stanfordnlp.github.io/CoreNLP/) and unzip the package in a local folder on your machine.
Add the distribution directory to your CLASSPATH as follows:
export CLASSPATH=$CLASSPATH:/path/to/stanford-corenlp-4.3.0/*:

2. Create a java class called "nlpPipeline.java" and a class called "SentenceSentiment.java".

3. Copy and paste the code in this repo from the same java files to your local file.

4. Run these commands on your terminal: 

$ javac nlpPipeline.java
$ javac SentenceSentiment.java 
$ java SentenceSentiment

You should be able to see the sentences in "SentenceSentiment.java" and the corresponding sentence sentiment on your commandline.

