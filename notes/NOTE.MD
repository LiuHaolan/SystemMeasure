time -o [file] : to measure time
taskset -c n ./prog : only use n cores to run this program

sudo -E: preserve the existed environment variable

->source .sh
->.sh
difference: source is working on the current directory, $PWD is where you execute this shell scripts, while .sh means cd and source

numactl --hardware 
-> if more than one nodes, it's NUMA architecture
Note: please write to emulated persistent memory.
