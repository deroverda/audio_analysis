# audio_analysis
a python script to analyze all flacs within a folder such as sample rate, bit, true peak lvl, loudness range, file integrity etc.

here's an example of what the script shows when running it in a folder with 3.flacs:


``` type: audioinfo
version: 1

summary:
  total_files: 3
  total_duration: 0:16:27
  sample_rate: 48000, 44100
  bit_depth: 16, 24
  channels: 2

track_details:
Track: STYX2018-06-10-t04.flac
  Duration: 0:04:40
  Total Samples: 12382692
  Sample Rate: 44100 Hz
  Bit Depth: 16 bits
  Channels: 2
  Bit Rate: 788k
  True Peak Level: -0.5
  CRC32: 83B339D8
  MD5: 8f6e72096a6e2298313017cde4c4ab85
  Integrated Loudness: -14.4 LUFS
  Loudness Range (LRA): 13.4 LU
  Channel Layout: Multi-channel
  File Integrity: OK

Track: Styx_2011-07-08_t07.flac
  Duration: 0:08:06
  Total Samples: 21462000
  Sample Rate: 44100 Hz
  Bit Depth: 16 bits
  Channels: 2
  Bit Rate: 837k
  True Peak Level: 0.0
  CRC32: 80F9ABF3
  MD5: c4192f1e30be3a7c8fabe3381193df13
  Integrated Loudness: -16.2 LUFS
  Loudness Range (LRA): 12.7 LU
  Channel Layout: Multi-channel
  File Integrity: OK

Track: styx 2022-06-14 kansas city - cmc-25 t09 stage chatter.flac
  Duration: 0:03:41
  Total Samples: 10640000
  Sample Rate: 48000 Hz
  Bit Depth: 24 bits
  Channels: 2
  Bit Rate: 1.45M
  True Peak Level: 0.3
  CRC32: 035BF7B1
  MD5: 02b2a1a95c060bbc98e161c17bc56cba
  Integrated Loudness: -27.3 LUFS
  Loudness Range (LRA): 9.8 LU
  Channel Layout: Multi-channel
  File Integrity: OK


!!!UPDATE!!!!!!!!
created a exe file so you dont need all the dependencies. just download the .exe file and place it in the folder with the flac files. 

