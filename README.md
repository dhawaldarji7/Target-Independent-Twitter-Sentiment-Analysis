# Target-Independent-Twitter-Sentiment-Analysis

This is a project I developed as a part of my CS 753/853: Topics / Information Retrieval Fall 2019 course at the University of New Hampshire

Requirements:
Maven 3.6.0
Java 11.0.4
Lucene 8.2.0

How to Run:

clone this repository.

To run this programon Linux, Maven has to be installed

Instructions to install Maven:

sudo apt install maven

To compile this program, run the following command:

mvn clean compile assembly:single

The codestub is divided into two parts:

1. Sentiment Analysis without query expansion
    java -Xmx50g -cp target/IR-Lucene-0.0.1-SNAPSHOT-jar-with-dependencies.jar Main

2. Sentiment Analysis using query expansion
    Please change the below line in properties.xml with the path in your machine.
    <param name="dictionary_path" value="path\to\dict"/>

    java -Xmx50g -cp target/IR-Lucene-0.0.1-SNAPSHOT-jar-with-dependencies.jar Main2

Run files will be created for all models.

NOTE: The project is no longer maintained.