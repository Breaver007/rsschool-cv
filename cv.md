1.Alex Parfenyuk 2.mail parkyr100@gmail.com 3.Work as a novice programmer. I want to develop and learn something new because have interest. (Работаю начинающим программистом. Хочу развиваться и познавать что-то новое т.к. есть интерес.) 4.Java,C++,C#,JavaScript,PHP,VBA,Delphi 5.С# public static SqlCeConnection BD = new SqlCeConnection(@"Data Source = avtosolon.sdf"); BD.Open(); this.chart1.Series[0].Points.Clear(); SqlCeDataReader chitalka; SqlCeCommand zapros1 = new SqlCeCommand("select DISTINCT stah from sotrydniki", BD); chitalka = zapros1.ExecuteReader(); int fam = 0; while (chitalka.Read()) fam++; for (int i = 1; i <= fam; i++) {

            SqlCeCommand zapros = new SqlCeCommand("select count(*) from sotrydniki where stah=" + i.ToString(), BD);
            
            chitalka = zapros.ExecuteReader();
            if (chitalka.Read())
            
                this.chart1.Series[0].Points.AddXY(i, chitalka[0]);
                    
        }
        BD.Close();

6.Work experience 1 year no projects. 7.Средне-специаьное (заочное образование 2 курс) 8.Английский язык (Weak).
