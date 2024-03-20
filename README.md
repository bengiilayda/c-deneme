
//c# ile not ortalamasi bulma 
namespace floatdoubleyt7
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {

            /*double x = 5.123456765668; ///15 satir alabilir
            float y = 5.44152132f; ////7 satir alabilir
            textBox1.Text = Convert.ToString(y);*/

            /* char c;
             c = 't'; 
             textBox1.Text = Convert.ToString(c); ///1 bitelık veri tutup memory az olmasını istiyorsak char kullanırız.
            */

            /*int not1, not2 , not3;
            double ort;
            not1 = Convert.ToInt32(textBox3.Text);
            not2 = Convert.ToInt32(textBox4.Text);
            not3 = Convert.ToInt32(textBox2.Text);

            ort = (double) (not1 + not2 + not3) / 3;
            textBox1.Text=Convert.ToString(ort);*/

            double not1, not2, not3;
            double ort;

            not1=Convert.ToDouble(textBox3.Text);
            not3=Convert.ToDouble(textBox2.Text);
            not2=Convert.ToDouble(textBox3.Text);

             ort= (double) (not1 + not2 + not3) / 3;
            textBox1.Text=Convert.ToString(ort);




        }

        private void textBox3_TextChanged(object sender, EventArgs e)
        {

        }
    }
}

