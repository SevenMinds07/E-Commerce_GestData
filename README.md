# pipeline-dataops-ecommerce
Repositorio mostrando los cambios y el proyecto de E-commerce para la materia de Gestión de Datos
A la hora de conectar, debes descargar y subir a Drive el Excel para conectarlo a la instancia N8N

Link Trello: https://trello.com/invite/b/6a16359bda094068c948aca5/ATTId45c9b117cd18b093712a9aef9f33966D8923F53/gestion-ecommerce


Uso Docker a través de CodeSpace de GitHub:
# instalar (si no está)
npm install -g n8n

# iniciar el servidor n8n
n8n start

# en otra terminal: importar el workflow
n8n import:workflow --input="Pipeline DataOps E-commerce ITY1101.json"
