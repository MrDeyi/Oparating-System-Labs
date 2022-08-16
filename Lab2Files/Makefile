all:hello_world arguments cpu fork_test wait_test zombie test1 test2
hello_world:hello_world.c
	gcc hello_world.c -Wall -Wextra -pedantic -o hello_world
arguments:arguments.c
	gcc arguments.c -Wall -Wextra -pedantic -o arguments
fork_test:fork_test.c
	gcc fork_test.c -Wall -Wextra -pedantic -o fork_test
cpu:cpu.c
	gcc cpu.c -Wall -Wextra -pedantic -o cpu
wait_test:wait_test.c
	gcc wait_test.c -Wall -Wextra -pedantic -o wait_test
zombie:zombie.c
	gcc zombie.c -Wall -Wextra -pedantic -o zombie
test1:test1.c
	gcc test1.c -Wall -Wextra -pedantic -o test1
test2:test2.c
	gcc test2.c -Wall -Wextra -pedantic -o test2
clean:
	rm -f hello_world arguments fork_test zombie test1 test2