- यदि आप पाइथन में दो स्ट्रिंग्स को एक साथ जोड़ना चाहते हैं, तो अक्सर **कंकटेनशन**का उपयोग करना सबसे सरल है। उदाहरण के लिए, आप निम्न कार्य कर सकते हैं:

    ```python
    sentence = 'The quick brown fox' + ' jumped over the lazy dog'
    print(sentence)
    ```

- यह दो स्ट्रिंग्स को एक स्ट्रिंग में बदल देगा और इसे वापस कर देगा।

    ```python
    'The quick brown fox jumped over the lazy dog'
    ```

- कभी-कभी आप दो स्ट्रिंग्स के बीच में अक्षर/शब्द को सम्मिलित करना चाहते हैं, जिस स्थिति में `.format()` स्ट्रिंग मेथड आसान है। आप प्लेसहोल्डर के रूप में मंझले कोष्ठक के अंदर संख्या के साथ `.format()` उपयोग कर सकते हैं। उदाहरण के लिए:

    ```python
    sentence = 'The {0} {1} fox jumped over the {2} dog'
    ```

- यदि आप `.format()` मेथड मे व्य्लुज देते हैं, तो यह उन्हें स्ट्रिंग में सम्मिलित करेगा। उदाहरण के लिए, निम्नलिखित मेथड मूल वाक्य लोटाएगा...

    ```python
    sentence.format('quick', 'brown', 'lazy)
    ```

- ... लेकिन आप इसे आसानी से किसी और स्ट्रिंग में बदल सकते हैं, उदाहरण के लिए:

    ```python
    sentence.format('slow', 'green', 'naughty')
    ```

- आप अन्य ओब्जेक्ट्स को वेरिएबल्स में भी पास कर सकते हैं।

    ```python
    foo = 'tired'
    bar = 'purple'
    baz = 'hairy'
    sentence.format(foo, bar, baz)
    ```
