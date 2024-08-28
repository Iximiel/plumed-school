Stderr for source:  Tutorial.md_working_2.dat   
Download: [zipped raw stdout](Tutorial.md_working_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](Tutorial.md_working_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():  std::bad_alloc

The above exception was the direct cause of the following exception:

(tools/NeighborList.cpp:117) void PLMD::NeighborList::initialize()
An error happened while allocating the neighbor list, please decrease the number of atoms used
[fv-az1427-785:05211] *** Process received signal ***
[fv-az1427-785:05211] Signal: Aborted (6)
[fv-az1427-785:05211] Signal code:  (-6)
[fv-az1427-785:05211] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9b6f642520]
[fv-az1427-785:05211] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9b6f6969fc]
[fv-az1427-785:05211] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9b6f642476]
[fv-az1427-785:05211] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9b6f6287f3]
[fv-az1427-785:05211] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f9b6faa2b9e]
[fv-az1427-785:05211] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f9b6faae20c]
[fv-az1427-785:05211] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f9b6faae277]
[fv-az1427-785:05211] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9b6faae52b]
[fv-az1427-785:05211] [ 8] plumed_master(+0x14274)[0x556a113bd274]
[fv-az1427-785:05211] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9b6f629d90]
[fv-az1427-785:05211] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9b6f629e40]
[fv-az1427-785:05211] [11] plumed_master(+0x14ed5)[0x556a113bded5]
[fv-az1427-785:05211] *** End of error message ***
</pre>
{% endraw %}
