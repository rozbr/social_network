#<h1>social_network</h1>
#<h3>User Class</h3>
#<h3>Graphic-User Interface</h3>
#<h3>Comments nature: </h3> 
	#			Instanciates a user with a given number of informations
	#			Inherits from classes: 
	#									People
	#									Page Admin 
	#									Group Admin
	#									Blocked User for 30 days 
	
	class generic_user:

		def __init__(self, name, age, occupation, ..., ..., ...):

			#public variables
			self.name = name
			...

			#protected variables
			self._age = age
			...

			#private variables
			self.__occupation = occupation
			...

		#modify any solicited settings 
		def set_settings(self):
			pass

		#responsible for get the current settings status
		def get_settings(self):
			pass
