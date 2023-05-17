# Modified
The dataset has been modified and enhanced by StellarDragon for his undergraduate thesis at Nanjing University. Specific modifications include, but are not limited to: correcting texts that do not conform to the formatting requirements, replacing full-width letters, characters, and numbers with half-width ones, and correcting some questions with obvious logical mistakes. After repairing the Chinese dataset, I used advanced tools such as ChatGPT for a more accurate translation. Through practical testing, the same model achieved an accuracy improvement of up to 5% on the dataset I modified compared to the original dataset.

# LogiQA
This dataset consists of 8,678 QA instances.(Train:7376; Eval:651; Test:651)

The files is divided into English version: Train.txt, Eval.txt, Test.txt, and Chinese version: zh_train.txt, zh_eval.txt, zh_test.txt. 

Each 8 lines constitute an example of a problem.  (8,678 * 8 = 69,424)

In each 8 lines: 

                 The first line is blank line;

                 The second is right choice;

                 The third is context;
 
                 The fourth is question;
    
                 The remaining four lines are four options.
