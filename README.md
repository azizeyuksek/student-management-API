### Student Management API
Bu projem Flask kullanılarak geliştirdiğim basit bir REST API örneğidir.

## Projemin Özellikleri:

 GET  ile listedeki tüm öğrencileri gösterilir.
 POST  ile listeye yeni öğrenci eklenir.
 PUT ile öğrenci güncellenebilir.
 DELETE ile öğrenci silinir.

## Kullanılan Teknolojiler

 Python
 Flask
 JSON
 Postman ' dır.

## Nasıl Çalıştırılır ?

```bash
pip install flask
python app.py


## Örnek JSON response 

GET /students

[
  {
    "id": 1,
    "name": "Azize",
    "department": "Computer Engineering"
  }
]

<img width="1600" height="988" alt="screenshots_get" src="https://github.com/user-attachments/assets/b4e2f797-e532-4226-ae85-f71f218df377" />
