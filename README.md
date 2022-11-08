# kuy_production

This notebook contains code written in mentorship with Raksit Lau-Preechathammarach. 
The raw data are samples of speech from native speakers of Kuy, that were then analyzed using VoiceSauce to produce a series of acoustic measurements. 
This notebook takes cleaned up VoiceSauce measurements and phonological labels, in particular categorical "breathy" vs. "modal" voice quality as *intended*
by speakers, and trains two LDAs using one set of acoustic measurements or another, in order to determine which set of acoustic measurements
is most utilized by each speaker to produce this phonological contrast.
