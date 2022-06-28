# django_notes

- What is the difference in implementation and functioning of a `MultipleChoiceField` and a `ListField` with `ChoiceField` as child class in django rest framework?
- Primary key and foreign key field generated by a ModelSerializer is always a read only field. If we want user to input a foreign key id, we have to explicitly declare a field for it on the ModelSerializer

# CSRF
- In Django Rest Framework, all the `APIView` classess will be `csrf_exempt` by default.
