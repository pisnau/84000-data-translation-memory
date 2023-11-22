# 84000/data-translation-memory

84000 Translation Memory files

Explanation of file versions “-v1”, “-v2”, etc.. :
The versions listed after the file names reflect the method for generating the TM:
- “-v1”, **creationtool="84000-translation-memory"** - these were created manually using an early 84000 app around 2018 that highlighted segments in the source and target. There may some gaps between segments a slightly messy data. Segments have ids according to Tibetan folio.  
- “-v2”, **creationtool="InterText"** - these were created manually using the InterText method documented [here](https://github.com/84000/translation-memory-resources/wiki/TM-Editor-Guidelines#1-instructions-for-aligning-tms-from-pre-segmented-text-files-using-intertext). Contains some tags from the original TEI. Source segments include tags for Tibetan folio references, and the target segments contain tags for milestones and notes with ids. Segments that were translated from an alternate source but still matched to the Tibetan Degé e-text are marked as type=”alternative-source”. The segmentation should be more consistent than v1 as we attempted to follow a standard as much as was pragmatically possible. Segments have ids according to Tibetan folio.  
- “-v3”, **creationtool="linguae-dharmae/84000"** - these were created with machine alignment using Mitra. These alignment should be approximately 90% accurate. All TMs created in 2023 onward will include tags from the original TEI including the Tibetan folio references in the source and tags for notes and milestones in the target; however, TMs created before 2023 do not include these tags. Segments have ids according to the milestones in English translation.  
<<<<<<< HEAD
- “-v4” **creationtool="monlam-ai/84000"** - these were created by manually post correcting the machine alignment from Mitra, and should be 99-100% accurate. They include all the tags from the original TEI mentioned above. Segments have ids according to the milestones in English translation. We intend to eventually update all the v3 TMs to v4.  
=======
- “-v4” **creationtool="monlam-ai/84000"** - these were created by manually post correcting the machine alignment from Mitra, and should be 99-100% accurate. They include all the tags from the original TEI mentioned above. Segments have ids according to the milestones in English translation. We intend to eventually update all the v3 TMs to v4.  
>>>>>>> 918cbc77031c8b54d13a5267e1bb8d09ff6523d9
