
    def __init__(self):
        self.nombre = "cesar martinez"
        self.edad = 21
        self.email = "ma472168@uaeh.edu.mx"
        self.universidad = "universidad autonoma del estado de hidalgo"
        self.carrera = "ingenieria en sistemas computacionales"
        self.optativas = ["sistemas multiagentes", "diseño de redes", "administracion de redes"]
        self.ubicacion = "mineral de la Reforma, Pachuca, Hidalgo"
        self.pais = "mexico"
        self.disponibilidad = "disponible para trabajar en cualquier parte de la republica mexicana"
        self.idiomas = ["español", "ingles conversacional"]

    def experiencia(self):
        return {
            "servicio social": "desarrollador web en el departamento de planeacion de la universidad",
            "proyectos personales": ["paginas web estaticas", "aplicaciones web con Django", "sistemas de gestion de bases de datos"],
            "participaciones": ["hackatones (uaeh)", "concursos de programacion (uaeh)", "proyectos de investigacion", "cpcs (competencias de programacion competitiva)"],
            "soporte tecnico familiares": "brindar soporte tecnico a familiares y amigos en problemas informaticos basicos"
        }
    
    def educacion(self):
        return {
            "bachillerato": "Técnico en Programación en el Colegio de Estudios Científicos y Tecnológicos del Estado de Hidalgo",
            "universidad": "licenciatura en ciencias computacionales en la Universidad Autónoma del Estado de Hidalgo", 
            "certificaciones": ["CCNA (Cisco Certified Network Associate)"]
        }

    def lenguajes(self):
        return ["python", "java", "c++", "javascript", "html", "css", "sql"]
    
    def herramientas(self):
        return ["git", "github", "visual studio code", "mysql workbench", "virtualbox", "cisco packet tracer"]
    
    def hobbies(self):
        return ["leer", "programar", "jugar videojuegos", "ver series y peliculas", "escuchar musica"]
    
    def habilidades(self):
        return {
            "trabajo en equipo": "capacidad para trabajar en equipo y colaborar con otros",
            "comunicacion": "buenas habilidades de comunicacion verbal y escrita",
            "resolucion de problemas": "habilidad para resolver problemas de manera efectiva",
            "adaptabilidad": "capacidad para adaptarse a nuevos entornos y aprender rapidamente"
        }
