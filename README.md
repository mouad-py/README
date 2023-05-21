class Attributes(jspluspy):
	@staticmethod
	def contact() -> tuple:
	    discord  = "v1snj4#2663"
	    telegram = "t.me/avisnjicc"
	    proton   = "github@moudad-py"
	    
	    return discord, telegram, proton
	
	@staticmethod
	def life() -> tuple:
		langs         = ['Serbian', 'French', 'German', 'Spanish', 'English']
		age           = 21
		
		return langs, age
	
	@staticmethod
	def coding() -> tuple:
		langs = {
			'expert':   ['python'],
			'intermediate': ['go', 'js'],
			'learning': ['c', 'c++', 'c#', 'asm', 'java']
		}
		specialities  = ['web/app reverse engineering', 'fullstack']
		environnement = ['vscode']
		
		return langs, specialities, environnement
