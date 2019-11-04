# Remove-a-char-from-a-string




           


            string myString = "w3resource";
            Console.WriteLine(myString.Remove(1, 1));
            Console.WriteLine(myString.Remove(9, 1));
            Console.WriteLine(myString.Remove(0, 1));



            // OR

            

            Console.WriteLine(remove_char("w3resource", 1));
            Console.WriteLine(remove_char("w3resource", 9));
            Console.WriteLine(remove_char("w3resource", 0));
        }

        public static string remove_char(string str, int n)
        {
            return str.Remove(n, 1);
        }
