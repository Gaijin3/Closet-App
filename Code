import tkinter as tk

def say_hello():
    label.config(text="Im Gay!")

def say_goodbye():
    label.config(text="Wait! Nvm")
    root.after(2000, root.destroy)  # Close the window after 2 seconds

# Create the main window
root = tk.Tk()
root.title("Closet App")

# Create a label widget
label = tk.Label(root, text="Click the buttons to show your true self!")
label.pack(padx=20, pady=20)

# Create buttons with different functionalities
hello_button = tk.Button(root, text="Say Im Gay", command=say_hello)
hello_button.pack(padx=10, pady=5)

goodbye_button = tk.Button(root, text="Say Wait", command=say_goodbye)
goodbye_button.pack(padx=10, pady=5)

# Start the application loop
root.mainloop()
