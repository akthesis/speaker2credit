# Speaker2Credit 

## Speaker2Credit - credibility vectors for fake news detection

This dataset is part of a paper published at DSJM 2018 and an ongoing master thesis.

*Speaker2Credit* is based on the publicly available data from PolitiFact.com and the benchmark data set [LIAR](https://www.cs.ucsb.edu/~william/data/liar_dataset.zip) (Wang 2017).
Given a speaker's name, job title, party affiliation and home state one can look up their corresponding credibility vector using *Speaker2Credit*.

## Content

The dataset consists of 10 tab-separated columns

4 columns to identify the speaker:
* speaker	(lowercase, hyphenated full name of the speaker)
* speakers_job	(official job title)
* state_info (home state of speaker)
* party_affiliation

6 alphabetically sorted columns that make up the credit vector:
* barely_true_cnt	
* false_cnt	
* half_true_cnt	
* mostly_true_cnt	
* pants_on_fire_cnt	
* true_cnt


## References

If you use this dataset, please cite the following paper:

``` 
@InProceedings{kirilin2018exploiting,
 author =  {Kirilin, Angelika  and  Strube, Micheal},
 title = 	 {Exploiting a Speaker’s Credibility to Detect Fake News},
 booktitle={Proceedings of Data Science, Journalism \& Media workshop at KDD (DSJM’18)},
 year = 	 2018
}
```
