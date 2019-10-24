# FreeDocOn crée une base de données pour un site sur le modèle Doctolib avec des docteurs et des patients, qui peuvent prendre rendez-vous ensemble.

Tables

Les différentes tables :

doctors
patients
cities
appointments
specialties
doctor_specialties
Relations

1-to-n :

cities - doctors
cities - patients
cities - appointments
n-to-n :

doctors - patients (liés par appointments)
doctors - specialties (liés par doctor_specialties)
