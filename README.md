# ProgrammingExam
Albader_Berika_programming_2023 w66720
.Select(x => x.Price + ";" + x.Date.ToString("yyyy/MM/dd") + ";" + x.Exptype);

            textBox2.Text = string.Join("\r\n", res);

            var res1 = expenses();
            var totalexps = res1.Sum(x => x.Price);
            textBox2.Text += "total expense " + totalexps;
        }

        public List<exp> expenses()
