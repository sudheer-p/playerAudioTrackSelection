# playerAudioTrackSelection
 Player Plugin to set the audio track based on the parameter password from the URL

- The desired audio track language can be passed via the URL in two ways
a) As a query parameter.
   e.g: https://hdbfbank.com/xyz.html?videoId=488484&anotherParam=xx&lang=hi
   * Important : the key should be 'lang' or 'language', and the value should be the language code as mentioned in ISO 639-1
b) Language code can be passed as part of the URL Pathname. Again the code shall follow ISO 639-1
   e.g: https://hdfcbank.com/en/video/abc.html
   *Important: the language code shall be the first entry in the path name.
   The following is INVALID:  htts://hdfcbank.com/video/en/abc.html



 
