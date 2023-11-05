
![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


# SAiF-GPT

Project created for AECTech Hackathon 2023 @ New York.

SAiF-GPT aims to provide a solution for using Chat GPT in a secure and compliant manner, even when dealing with sensitive information. 
To ensure that corporate policies and NDAs are respected, the code and process automate entity detection and anonymization by replacing them with analogous values.
The end goal is to allow AEC industry to use AI technology like ChatGPT for document analysis while protecting confidential data.

The workflow consists of:
1. Text uploaded undergoes analysis by an NLP (Natural Language Processing) model to pinpoint names of individuals, locations, and email addresses.
2. Detected entities within the text are substituted with generic placeholders prior to being uploaded to GPT.
3. User prompts are similarly analyzed, and any discovered entities are replaced with placeholders before submission to GPT.
4. Upon receiving the response from GPT, all generic placeholders are reverted to their original names before being displayed to the user.

## Known Limitations
- Some cases of misclassified entities. (However, all entities are anonymized)


## Usage/Examples & Future development ideas
The application could be extended to anonymize additional patterns.


## Presentation

You can access the [Presentation pdf here.](https://github.com/agusaboy)

## Team

- [Agustina Aboy](https://github.com/agusaboy)
- [Alexis Kotzambasis](https://github.com/lexiko80-LPA) 
- [Aman Sharma](https://github.com/aspeculat0r)
- [Carlos Luiz Amaral](https://www.github.com/closa1211)
- [Dan Miller](https://www.github.com/djmillerDeg)
- Kodai Endo / ek819@outlook.com
- [Omid Sajedi](https://github.com/ssajedi)
- R Yamashita / intaro0626@gmail.com
- [Samuel Winson Tanuwidjaja](https://www.github.com/samuelwt)
- [Sierra Davis](https://www.github.com/sierra-md)

Proof we were here: 

ADD PHOTOS HERE! 

## Acknowledgements

✨ Special thanks to: 
- Tamaho for helping with team communication with translations.
- Alexander Matthias Jacobson for his initial insight on the brainstorming and being the brave on to jump out of the boat.

## License

[MIT](https://github.com/ssajedi/AInonymous/blob/main/LICENSE)


