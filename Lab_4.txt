import menu_script

def main():
    quit_program = False
    while not quit_program:
        menu_script.show_menu()
        choice = input("Choose a menu item: ")
        if choice == "1":
            print("You've chosen item #1")
        elif choice == "2":
            print("You've chosen item #2")
        elif choice == "0":
            print("Bye-bye!")
            quit_program = True
        else:
            print("Invalid choice.")
    print("Exiting the program...")

if __name__ == "__main__":
    main()
