<table>
  <tr>
    <th></th>
    <th>Model</th>
    <th colspan="2">Accuracy</th>
    <th colspan="2">Precision</th>
    <th colspan="2">Recall</th>
    <th colspan="2">F1 Score</th>
  </tr>
  <tr>
    <th></th>
    <th></th>
    <th>Training</th>
    <th>Testing</th>
    <th>Training</th>
    <th>Testing</th>
    <th>Training</th>
    <th>Testing</th>
    <th>Training</th>
    <th>Testing</th>
  </tr>
  <tr>
    <td>spilitting on spaces<br>snow ball stemmmer</td>
    <td>SVM rbf</td>
    <td>0.67</td>
    <td>0.66</td>
    <td>0.68</td>
    <td>0.67</td>
    <td>0.66</td>
    <td>0.66</td>
    <td>0.67</td>
    <td>0.66</td>
  </tr>
  <tr>
    <td>spilitting on spaces<br>lemmatizer</td>
    <td>SVM rbf</td>
    <td>0.72</td>
    <td>0.70</td>
    <td>0.73</td>
    <td>0.71</td>
    <td>0.71</td>
    <td>0.70</td>
    <td>0.72</td>
    <td>0.70</td>
  </tr>
  <tr>
    <td>stanza tokenizer<br>wordnet lemmatizer</td>
    <td>SVM rbf</td>
    <td>0.71</td>
    <td>0.70</td>
    <td>0.72</td>
    <td>0.71</td>
    <td>0.71</td>
    <td>0.70</td>
    <td>0.71</td>
    <td>0.69</td>
  </tr>
  <tr>
    <td>stanza tokenizer<br>stanza lemmatizer</td>
    <td>SVM rbf</td>
    <td>0.72</td>
    <td>0.70</td>
    <td>0.73</td>
    <td>0.72</td>
    <td>0.71</td>
    <td>0.70</td>
    <td>0.72</td>
    <td>0.69</td>
  </tr>
  <tr>
    <td>nltk tokenizer<br>WordNetLemmatizer<br>nouns only</td>
    <td>SVM rbf</td>
    <td>0.66</td>
    <td>0.66</td>
    <td>0.67</td>
    <td>0.66</td>
    <td>0.66</td>
    <td>0.66</td>
    <td>0.66</td>
    <td>0.65</td>
  </tr>
  <tr>
    <td>nltk tokenizer<br>WordNetLemmatizer<br>nouns and verb only</td>
    <td>SVM rbf</td>
    <td>0.70</td>
    <td>0.69</td>
    <td>0.71</td>
    <td>0.70</td>
    <td>0.69</td>
    <td>0.69</td>
    <td>0.70</td>
    <td>0.69</td>
  </tr>
  <tr>
    <td>nltk tokenizer<br>WordNetLemmatizer<br>verb only</td>
    <td>SVM rbf</td>
    <td>0.41</td>
    <td>0.40</td>
    <td>0.39</td>
    <td>0.38</td>
    <td>0.40</td>
    <td>0.40</td>
    <td>0.39</td>
    <td>0.38</td>
  </tr>
  <tr>
    <td>nltk tokenizer<br>Snow Ball Stemmer<br>nouns only (1-3) ngram</td>
    <td>SVM rbf</td>
    <td>0.80</td>
    <td>0.76</td>
    <td>0.80</td>
    <td>0.78</td>
    <td>0.80</td>
    <td>0.76</td>
    <td>0.79</td>
    <td>0.75</td>
  </tr>
  <tr>
    <td>nltk tokenizer<br>Snow Ball Stemmer<br>nouns and verb only (1-3) ngram</td>
    <td>SVM rbf</td>
    <td>0.79</td>
    <td>0.74</td>
    <td>0.79</td>
    <td>0.75</td>
    <td>0.79</td>
    <td>0.74</td>
    <td>0.77</td>
    <td>0.73</td>
  </tr>
  <tr>
    <td>nltk tokenizer<br>Snow Ball Stemmer<br>Adj only (1-3) ngram</td>
    <td>SVM rbf</td>
    <td>0.72</td>
    <td>0.49</td>
    <td>0.72</td>
    <td>0.46</td>
    <td>0.72</td>
    <td>0.49</td>
    <td>0.71</td>
    <td>0.46</td>
  </tr>
  <tr>
    <td>nltk tokenizer<br>only (1-3) ngram</td>
    <td>SVM rbf</td>
    <td>0.81</td>
    <td>0.79</td>
    <td>0.81</td>
    <td>0.81</td>
    <td>0.81</td>
    <td>0.79</td>
    <td>0.79</td>
    <td>0.78</td>
  </tr>
  <tr>
    <td>nltk tokenizer<br>Snow Ball Stemmer<br>ngram (2-3) no stemming & nouns stemmed only</td>
    <td>SVM rbf</td>
    <td>0.84</td>
    <td>0.82</td>
    <td>0.85</td>
    <td>0.83</td>
    <td>0.84</td>
    <td>0.82</td>
    <td>0.83</td>
    <td>0.81</td>
  </tr>
  <tr>
    <td>Spacy<br>Dependency Tree</br>Word - Head - Head Of Head</td>
    <td>SVM rbf</td>
    <td>0.81</td>
    <td>0.75</td>
    <td>0.76</td>
    <td>0.75</td>
    <td>0.77</td>
    <td>0.79</td>
    <td>0.80</td>
    <td>0.80</td>
  </tr>
  <tr>
    <td>Spacy<br>Dependency Tree</br>Word - Head - Deprel</td>
    <td>SVM rbf</td>
    <td>0.86</td>
    <td>0.72</td>
    <td>0.76</td>
    <td>0.71</td>
    <td>0.80</td>
    <td>0.73</td>
    <td>0.80</td>
    <td>0.76</td>
  </tr>
  <tr>
    <td>Spacy<br>Dependency Tree</br>Word(POS) - Head(POS) - Deprel(POS) - Lemma</td>
    <td>SVM rbf</td>
    <td>0.81</td>
    <td>0.71</td>
    <td>0.76</td>
    <td>0.71</td>
    <td>0.81</td>
    <td>0.76</td>
    <td>0.86</td>
    <td>0.72</td>
  </tr>
  <tr>
    <td>Spacy<br>NER</br> ORG Only</td>
    <td>SVM rbf</td>
    <td>0.85</td>
    <td>0.30</td>
    <td>0.76</td>
    <td>0.25</td>
    <td>0.86</td>
    <td>0.26</td>
    <td>0.80</td>
    <td>0.22</td>
  </tr>
  <tr>
    <td>Stanza<br>NER</br> without(Date, Cardinal or person), 2-3 grams  and nouns only stemmed</td>
    <td>SVM rbf</td>
    <td> 0.81</td>
    <td>0.79</td>
    <td>0.81</td>
    <td>0.80</td>
    <td>0.79</td>
    <td>0.79</td>
    <td>0.80</td>
    <td>0.78</td>
  </tr>
  <tr>
    <td>Stanza<br>Dependency tree</br> without(punct and root)</td>
    <td>SVM rbf</td>
    <td> 0.61</td>
    <td>0.57</td>
    <td>0.62</td>
    <td>0.56</td>
    <td>0.61</td>
    <td>0.57</td>
    <td>0.59</td>
    <td>0.52</td>
  </tr>
    <tr>
    <td>Synset Names only</td>
    <td>SVM rbf</td>
    <td> 0.77</td>
    <td>0.68</td>
    <td>0.77</td>
    <td>0.66</td>
    <td>0.77</td>
    <td>0.68</td>
    <td>0.76</td>
    <td>0.65</td>
  </tr>
  <tr>
    <td>Synset Names only with pos tag</td>
    <td>SVM rbf</td>
    <td> 0.78</td>
    <td>0.67</td>
    <td>0.79</td>
    <td>0.65</td>
    <td>0.78</td>
    <td>0.67</td>
    <td>0.77</td>
    <td>0.64</td>
  </tr>
  
  <tr>
    <td>Synset Names only and Nouns Stemmed and 2-3 grams no stemming</td>
    <td>SVM rbf</td>
    <td> 0.83</td>
    <td>0.84</td>
    <td>0.83</td>
    <td>0.82</td>
    <td>0.83</td>
    <td>0.84</td>
    <td>0.82</td>
    <td>0.82</td>
  </tr>

  <tr>
    <td>Tuning stem_head_headofhead + ngram(2-3) + nouns stemmed only chi2</td>
    <td>SVM rbf</td>
    <td> 0.82</td>
    <td>0.81</td>
    <td>0.82</td>
    <td>0.82</td>
    <td>0.82</td>
    <td>0.81</td>
    <td>0.81</td>
    <td>0.79</td>
  </tr>

  <tr>
    <td>Tuning stem_head_headofhead + ngram(2-3) + nouns stemmed only classif</td>
    <td>SVM rbf</td>
    <td> 0.84</td>
    <td>0.83</td>
    <td>0.83</td>
    <td>0.83</td>
    <td>0.82</td>
    <td>0.83</td>
    <td>0.84</td>
    <td>0.84</td>
  </tr>
<tr>
  <td>Word2Vec Embeddings SVM g=2</td>
  <td>SVM rbf</td>
  <td> 1</td>
  <td>0.05</td>
  <td>1</td>
  <td>0.17</td>
  <td>1</td>
  <td>0.05</td>
  <td>1</td>
  <td>0.02</td>
</tr>
  <tr>
  <td>Word2Vec Embeddings SVM g=0.01</td>
  <td>SVM rbf</td>
  <td> 0.99</td>
  <td>0.53</td>
  <td>0.99</td>
  <td>0.52</td>
  <td>0.99</td>
  <td>0.53</td>
  <td>0.99</td>
  <td>0.51</td>
</tr>
  <tr>
  <td>Word2Vec Embeddings SVM</td>
  <td>SVM Linear</td>
  <td> 1</td>
  <td>0.47</td>
  <td>1</td>
  <td>0.50</td>
  <td>1</td>
  <td>0.47</td>
  <td>1</td>
  <td>0.48</td>
</tr>
  <tr>
  <td>Word2Vec Embeddings KNN 3</td>
  <td></td>
  <td> 0.66</td>
  <td>0.43</td>
  <td>0.69</td>
  <td>0.49</td>
  <td>0.66</td>
  <td>0.43</td>
  <td>0.65</td>
  <td>0.43</td>
</tr>
<tr>
  <td>Word2Vec Embeddings Deep learning</td>
  <td>MLPClassifier hidden 100 mxiter 500</td>
  <td> 1</td>
  <td>0.57</td>
  <td>1</td>
  <td>0.57</td>
  <td>1</td>
  <td>0.57</td>
  <td>1</td>
  <td>0.56</td>
</tr>

<tr>
  <td>Word2Vec Embeddings Deep learning</td>
  <td>MLPClassifier hidden 100 mxiter 500</td>
  <td> 1</td>
  <td>0.56</td>
  <td>1</td>
  <td>0.57</td>
  <td>1</td>
  <td>0.56</td>
  <td>1</td>
  <td>0.56</td>
</tr>
</table>

![image](https://github.com/user-attachments/assets/6faaa072-1252-4a4a-bbc1-12de78a46038)
![image](https://github.com/user-attachments/assets/f2c1112f-4b39-40a5-b61f-fbc49e756fa1)
![image](https://github.com/user-attachments/assets/a5735f0d-f4b6-453d-9b59-dc6fc9eb8496)
![image](https://github.com/user-attachments/assets/22d02054-f74f-4cac-9f6c-9b0790067fb7)
![image](https://github.com/user-attachments/assets/cf9d4675-c1e0-441c-9514-f0e56a7c340d)
![image](https://github.com/user-attachments/assets/4bb9bd7b-8a3d-43b7-a54b-6f68ceca6dfc)
![image](https://github.com/user-attachments/assets/bbd03fac-7f24-4759-b6d6-e2041b1545cf)
every thing
![image](https://github.com/user-attachments/assets/d6cd0ace-6a65-40df-b6ce-b8040d384c48)

2-gram Dep and nouns Stem
![image](https://github.com/user-attachments/assets/e2d51fe5-bd04-46f5-8699-d86e6e422cac)



2-gram Dep and nouns lemma 
![image](https://github.com/user-attachments/assets/85a0f630-2891-4565-b76b-ce3fdfcfb9c5)

![image](https://github.com/user-attachments/assets/0e460bcd-f1a5-4d18-8d08-7c9770fe61fe)
Top 20 NER Features
['ap', 'autocad', 'cisco', 'facebook', 'fmla', 'gaap', 'general_ledger', 'gl', 'google_analytics', 'hr', 'hris', 'instagram', 'medicare', 'navy', 'pr', 'quickbooks', 'shrm', 'solidworks', 'twitter', 'windows_server']


![image](https://github.com/user-attachments/assets/bcddc312-0529-4858-854f-2e60abcf7fcc)
![image](https://github.com/user-attachments/assets/a174fff9-3e07-4c4a-9a96-a3fd203192dc)
mutual_info_classif
![image](https://github.com/user-attachments/assets/42ea99f1-368c-4a0c-af2c-0f5fa3ed5796)
f_classif
![image](https://github.com/user-attachments/assets/f7dfdb95-9296-4f0d-8ba0-1a8b8419bf19)

![image](https://github.com/user-attachments/assets/aefa50eb-eb1c-418f-bb4c-1b7cc83b9448)

Confiusion metrix for Synset Names only and Nouns Stemmed and 2-3 grams no stemming
×آ
![image](https://github.com/user-attachments/assets/2c89cac9-3470-4a2c-a4bb-acbaf1c0cce7)
![image](https://github.com/user-attachments/assets/1f8298a9-6aa9-4eed-bf88-4ec94822daf5)




