# Text-Classification-Sanskrit
Using RNN to classify Sanskrit Words

## Background:
Amarakośaḥ (https://en.wikipedia.org/wiki/Amarakosha) is an ancient thesaurus in Sanskrit. It consists of 11580 words in all and 9031 unique
words. Amarakośaḥ cosists of three Kāṇḍas - Prathamakāṇḍa, dvitīyakāṇḍa and tṛtīyakāṇḍa (First, Second and Third). Each of these Kāṇḍas are further divided in to a total of 25 Vargas.

The varas are - Svargavargaḥ (heaven), Vyomavargaḥ (sky), Digvargaḥ (direction), Kālavargaḥ (time), Dhīvargaḥ (cognition), Śabdādivargaḥ (sound), Nāṭyavargaḥ (drama), Pātālabhogivargaḥ (nether world), Narakavargaḥ (hell), Vārivargaḥ (water), Bhūmivargaḥ (earth), Puravargaḥ (towns or Cities), Śailavargaḥ (mountains), Vanauṣadhivargaḥ (forests and medicines), Siṃhādivargaḥ (lions and other animals), Manuṣyavargaḥ (mankind), Brahmavargaḥ (priest tribe), Kṣatriyavargaḥ (military tribe), Vaiśyavargaḥ (business tribe), Śūdravargaḥ (mixed classes), Viśeṣyanighnavargaḥ (adjective), Saṁkīrṇavargaḥ (miscellaneous), Nānārthavargaḥ (polysemous), Avyayavargaḥ (indeclinables), Liṅgādisaṅgrahavargaḥ (gender).

## My Project:

In this project I am trying to use an LSTM based RNN model to classify sanskrit words based on this data from Amarakośaḥ.
Currently the model gives an accuracy of ~25%

### Dataset: From http://amara.aupasana.com/

## References: 
* Blog Article: Classifying Sanskrit Shlokas using an LSTM-based model - Analytics Vidhya
* Ph.D. Thesis: The Knowledge Structure in Amarakośa - University of Hyderabad
* Blog Article: Random Oversampling and Undersampling for Imbalanced Classification - Machine Learning Mastery
* Article: LSTM Recurrent Neural Networks, Towards Data Science - Medium
