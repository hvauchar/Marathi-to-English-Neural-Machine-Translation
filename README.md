# Marathi-to-English-Neural-Machine-Translation

Neural Machine Translation By Jointly Learning To Align And Translate based on Dzmitry Bahdanau, KyungHyun Cho, Yoshua Bengio attention mechanism
India is a multilingual nation with more than 120 major languages out of which 22 are official and others are dialectic languages even though these languages are spoken by majority of people in India use of these languages is underrepresented in cyberspace around 80% population is not language illiterate and multilinguality is a way to break this digital divide and move forward so as to provide universal access to all the people in their language of comfort

Multilinguality is a topic that is very close to my heart so as to advocate it more and more I’ve addressed the problem of neural machine translation in context of my mother tongue Marathi by implementing Bahdanau and Cho Bengio’s encoder-decoder based neural machine translation with attention mechanism that given Marathi sequence outputs the most probably English sentence!!!  It is working very fantastic and I have been through literature and several articles and I must say this is the first system to address this approach and in the context of Indian languages!!!!! 

![mar4](https://user-images.githubusercontent.com/49407332/80278596-65311580-8715-11ea-9741-ae5b7b315d98.png)

The most promising and happening part of it is that we can visualise that while translating input Marathi sequence to output English sentence how much attention is focused on the words in Marathi by every output word in English the system learns the word to word alignment between sources and target sequence by itself and by about chart we can visualise it the brighter the cell higher the attention on corresponding word alignment like in above example bolu in Marathi and talk is aligned the cell is bright same goes with Mala and Me!!!!!!! Isn’t that coool we take like years of efforts learning a language but it’s just a piece of cake for them  

## Through This approach we are able to overcome following problems in traditional Encoder Decoder architecture 

● A fixed-length context vector is the bottleneck for translating long sentences.

● Alignment mechanism, i.e. soft-search for a set of input words or annotations, enhances translation on longer sentences.

● Alignment models trained and evaluated on English-to-French translation achieve higher accuracy than fixed-length encoder-decoder models, especially on longer sentences. 


![gitgif](https://user-images.githubusercontent.com/49407332/80278468-1d5dbe80-8714-11ea-8e18-4c75f5077e6d.gif)

![mar2](https://user-images.githubusercontent.com/49407332/80278417-a45e6700-8713-11ea-8d3d-fd0fb8e73642.png)
![mar6](https://user-images.githubusercontent.com/49407332/80278418-a58f9400-8713-11ea-943e-3dc159dde695.png)
![plot1](https://user-images.githubusercontent.com/49407332/80278419-a6282a80-8713-11ea-8f57-0029cd5728b5.png)
![plot2](https://user-images.githubusercontent.com/49407332/80278420-a6282a80-8713-11ea-8092-e95844662a0d.png)
