Hello
test test

Lab 3 Pt.III

#38 
0: Acoustic Grand Piano
1: Bright Acoustic Pian
2: Electric Grand Piano
3: Honky-tonk Piano
4: Electric Piano 1
5: Electric Piano 2
6: Harpsichord
7: Clavi
8: Celesta
9: Glockenspiel
10: Music Box
11: Vibraphone
12: Marimba
13: Xylophone
14: Tubular Bells
15: Dulcimer

#39
It makes a piano sound

#40
They play piano sounds

#41 I see this:
Instrument number: 0
A (12) F (11) B (12) C (4) F (12) D (3) 
Yes, I could play the tune on a piano but not like the duration

#42 MidiPlayer midiPlay1 = new MidiPlayer();
SimpleTune simpleTu1 = new SimpleTune();
simpleTu1.addNote("C", 8);
simpleTu1.addNote("D", 8);
simpleTu1.addNote("E", 8);
midiPlay1.playTune(simpleTu1);

it started playing piano notes

#43 Yes, when I use the playTune method it replays the notes that I put on the SimpleTune

#44 Different piano notes start playing

#45 EXTERNAL: public void playTune(SimpleTune tune)
    INTERNAL: getNotes,

#46  Created a new class 

#47
public class TuneCreator
{
    // instance variables - replace the example below with your own
    private MidiPlayer player;

    /**
     * Constructor for objects of class TuneCreator
     */
    public TuneCreator()
    {
        
        player = new MidiPlayer();
    }

#48 public void CreateAndPlay()
    {
        
    }

#49 public void CreateAndPlay()
    {
        SimpleTune tune = new SimpleTune();
        
    tune.addNote("E", 4); 
    tune.addNote("D", 4); 
    tune.addNote("C", 4); 
    tune.addNote("B", 4); 
    tune.addNote("A", 4); 

        player.playTune(tune);
    }
}

#50 Changed it to 2

#51 

#52

#53 

#54 System.out.println("Instrument number: " + instrument);

#55

#56

#58

#58
