public class MainActivity extends AppCompatActivity {
    ...
    public void voteUdacicola(View view) {
        int udacicolaVotes = 0;
        udacicolaVotes = udacicolaVotes + 1;
    }

    public void votePepcity(View view) {
        int pepcityVotes;
        pepcityVotes = pepcityVotes + 1;
    }

    public void showMeVotes(View view) {
        display(udacicolaVotes + " vs. " + pepcityVotes);
    }
    ...
}
