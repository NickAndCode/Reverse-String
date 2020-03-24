public class Solution 
{
    public void ReverseString(char[] s) 
    {
        if (s == null) 
        {
            return;
        }
        for (int i = 0; i < s.Length / 2; i++) 
        {
            swap(s, i, s.Length - 1 - i);
        }
    }

    private void swap(char[] array, int i, int j) 
    {
        char ch = array[i];
        array[i] = array[j];
        array[j] = ch;
    }
}
