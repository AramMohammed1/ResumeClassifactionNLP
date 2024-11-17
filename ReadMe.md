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


</table>
