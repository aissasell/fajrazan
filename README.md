#  Fajrazan

**Fajrazan** is a bash script that hibernates the computer to ram and wakes it in a specific time and runs the azan with the voice of **Alafasy**.
Fajrazan doesn't calculate the time of the prayer but asks you to type it.



## Dependencies

 - **rtcwake**: It's the library that is used to hibernate the computer and wakes it. Comes by default in most distributions.
 - **date**: Used to convert a given date and time to a timestamp. Comes by default in most distributions.
 - **amixer**: Sets the the volume to 75% and unmute it. Comes by default in most distributions.
 - **mpg123**: Used to run the mp3 file in the console.

## Installation

```bash
git clone https://github.com/aissasell/fajrazan.git ~/fajrazan
```

## Usage

Run the following command
```bash
bash ~/fajrazan/fajr
```
It will ask you to type the time of the  fajr prayer. You can type any compatible format of the **date** library.
If you are in post midnight type:
```bash
tomorrow "the fajr time" 
```
If you are in after midnight type
```bash
today "the fajr time"
```

> Time must be in 24h format

It will asks you for root permissions. Type your password and hit enter.

Credits Salem Ben Aissa.