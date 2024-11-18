//TIP To <b>Run</b> code, press <shortcut actionId="Run"/> or
// click the <icon src="AllIcons.Actions.Execute"/> icon in the gutter.
package com.codewithmosh;

public class Main {
    public static void main(String[] args) {
       String sentence = "Java programming is fun and educational";

       String searchword = "fun";
       boolean containsword = searchword.contains(searchword);
       System.out.println("Does the sentence contains the word  " + searchword + " ? " + containsword);

       sentence = sentence.replace("educational", "awesome");
       System.out.println("'sentence' After replacing educational with awesome: " + sentence);


       int length = sentence.length();
       System.out.println("The Length of the string : " + sentence + " is : " + length + " letters ");


       String newsentence = sentence.substring(0, 18);
       System.out.println("Original Sentence: " + sentence);
       System.out.println("Shortened Sentence: " + newsentence);

    }
}
