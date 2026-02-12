technical-counselling-system/
│
├── main.py
├── student.py
├── counsellor.py
├── session.py
└── README.m
class Counsellor:
    def __init__(self, counsellor_id, name, expertise):
        self.counsellor_id = counsellor_id
        self.name = name
        self.expertise = expertise

    def display(self):
        print(f"ID: {self.counsellor_id}, Name: {self.name}, Expertise: {self.expertise}")
        class Counsellor:
    def __init__(self, counsellor_id, name, expertise):
        self.counsellor_id = counsellor_id
        self.name = name
        self.expertise = expertise

    def display(self):
        print(f"ID: {self.counsellor_id}, Name: {self.name}, Expertise: {self.expertise}")
        from student import Student
from counsellor import Counsellor
from session import CounsellingSession

print("Welcome to Technical Counselling System")

student = Student(1, "Kiran", "Software Development")
counsellor = Counsellor(101, "Anita Sharma", "Full Stack Development")

student.display()
counsellor.display()

session = CounsellingSession(
    student,
    counsellor,
    "Python Full Stack Developer"
)

session.summary()
