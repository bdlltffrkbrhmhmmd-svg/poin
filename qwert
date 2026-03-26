import tkinter as tk

# إنشاء النافذة الرئيسية
root = tk.Tk()
root.title("الواجهة الرئيسية")
root.geometry("400x300")
root.configure(bg="white")

# عنوان في أعلى الصفحة
title = tk.Label(root, text="الواجهة الرئيسية", font=("Arial", 18, "bold"), bg="white")
title.pack(pady=20)

# دالة زر إنشاء حساب جديد
def new_account():
    print("تم الضغط على زر إنشاء حساب جديد")

# دالة زر عرض المستخدمين
def show_users():
    print("تم الضغط على زر عرض كل المستخدمين")

# زر إنشاء حساب جديد (أخضر)
btn_new = tk.Button(
    root,
    text="إنشاء حساب جديد",
    bg="green",
    fg="white",
    font=("Arial", 14),
    width=20,
    height=2,
    command=new_account
)
btn_new.pack(pady=10)

# زر عرض كل المستخدمين (أخضر)
btn_users = tk.Button(
    root,
    text="عرض كل المستخدمين",
    bg="green",
    fg="white",
    font=("Arial", 14),
    width=20,
    height=2,
    command=show_users
)
btn_users.pack(pady=10)

# تشغيل البرنامج
root.mainloop()
