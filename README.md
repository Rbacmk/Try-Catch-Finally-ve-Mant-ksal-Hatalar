# Try-Catch-Finally-ve-Mant-ksal-Hatalar
//Try Catch Finally ve Mantıksal Hatalar
          /*  try { Hataya sebebiyet verme ihtimali olan kod }

            catch { Hata ile karşılaşıldığında ne yapılacağı buraya yazılır }

            finally { Hata olsun olmasın mutlaka yapılmasını istediğimiz işler varsa buraya yazarız }*/
            try
            {
 Console.WriteLine("Bir sayı giriniz:");
            int sayi=Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Girmiş oldugğunuz sayı:"+ sayi);
            }
            catch(Exception ex)
            {
                Console.WriteLine("Hata:" + ex.Message.ToString());

            }
           finally
            {
                Console.WriteLine("işlemini tamamlandı");
            }





            try
            {
                int a = int.Parse(Console.ReadLine());

                int b = int.Parse(Console.ReadLine());

                int c = a + b;

                Console.WriteLine(c);
            }
            catch (Exception ex)
            {
                Console.WriteLine("Bir Hata Oluştu: " + ex.Message);
            }
            finally
            {
                Console.WriteLine("İşlem tamamlandı.");
            }
