# WinForm-
namespace gaurikaform
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            String text = textBox1.Text;
            int num1 = Convert.ToInt32(textBox2.Text);
            MessageBox.Show("Hello Welcome in .Net word" + " " + text);

        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }
    }
}
