Stderr for source:  INSTRUCTIONS.md_working_4.dat   
Download: [zipped raw stdout](INSTRUCTIONS.md_working_4.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](INSTRUCTIONS.md_working_4.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1427-785:09183] *** Process received signal ***
[fv-az1427-785:09183] Signal: Aborted (6)
[fv-az1427-785:09183] Signal code:  (-6)
[fv-az1427-785:09183] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe657c42520]
[fv-az1427-785:09183] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe657c969fc]
[fv-az1427-785:09183] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe657c42476]
[fv-az1427-785:09183] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe657c287f3]
[fv-az1427-785:09183] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe6580a2b9e]
[fv-az1427-785:09183] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe6580ae20c]
[fv-az1427-785:09183] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe6580ae277]
[fv-az1427-785:09183] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe6580ae52b]
[fv-az1427-785:09183] [ 8] plumed_master(+0x14274)[0x55c3aa1bf274]
[fv-az1427-785:09183] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe657c29d90]
[fv-az1427-785:09183] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe657c29e40]
[fv-az1427-785:09183] [11] plumed_master(+0x14ed5)[0x55c3aa1bfed5]
[fv-az1427-785:09183] *** End of error message ***
</pre>
{% endraw %}
