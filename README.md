Visual Studio 2017 default FolderBrowserDialog not practical The component will be overridden



Add System.Drawing.Design Reference


if (folderBrowserDialog1.ShowDialog(this) == DialogResult.OK){
                MessageBox.Show("Choose：" + folderBrowserDialog1.DirectoryPath);
}
