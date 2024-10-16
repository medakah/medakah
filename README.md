



from typing import Tuple, List, Dict

class Medakah:
    pass

class Attributes(Medakah):
    @property
    def contact(self) -> Tuple[str, str, str]:
        telegram = "t.me/medakah_"
        return telegram

    @property
    def life(self) -> Tuple[List[str], int]:
        langs = ['German', 'English']
        age   = 21
		
        return langs, age
	
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'expert'      : ['python', 'go'],
            'intermediate': ['c', 'js', 'c++', 'java'],
            'learning'    : ['html', 'asm']
        }
        specialities  = ['Front-End Developer', 'Back-End Developer', 'Database Developer', 'DevOps Engineer', 'Mobile App Developer', 'Game Cheats Developer', 'Security Specialist']
        ide           = ['vscode']
        
	return langs, specialities, ide
