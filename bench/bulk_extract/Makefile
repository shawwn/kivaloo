.POSIX:
# AUTOGENERATED FILE, DO NOT EDIT
PROG=bulk_extract
MAN1=
SRCS=main.c elasticarray.c ptrheap.c timerqueue.c elasticqueue.c seqptrmap.c kvldskey.c monoclock.c sock.c warnp.c crc32c.c events_immediate.c events_network.c events_network_selectstats.c events_timer.c events.c network_read.c network_write.c netbuf_read.c netbuf_write.c wire_packet.c wire_readpacket.c wire_writepacket.c wire_requestqueue.c proto_kvlds_client.c
IDIRS=-I ../../libcperciva/datastruct -I ../../lib/datastruct -I ../../libcperciva/util -I ../../libcperciva/alg -I ../../libcperciva/events -I ../../libcperciva/network -I ../../lib/netbuf -I ../../lib/wire -I ../../lib/proto_kvlds
LDADD_REQ=

all:	${PROG}

install:${PROG}
	mkdir -p ${BINDIR}
	cp ${PROG} ${BINDIR}/_inst.${PROG}.$$$$_ &&	\
	    strip ${BINDIR}/_inst.${PROG}.$$$$_ &&	\
	    chmod 0555 ${BINDIR}/_inst.${PROG}.$$$$_ && \
	    mv -f ${BINDIR}/_inst.${PROG}.$$$$_ ${BINDIR}/${PROG}

clean:
	rm -f ${PROG} ${SRCS:.c=.o}

${PROG}:${SRCS:.c=.o}
	${CC} -o ${PROG} ${SRCS:.c=.o} ${LDADD_EXTRA} ${LDADD_REQ} ${LDADD_POSIX}

main.o: main.c ../../libcperciva/events/events.h ../../lib/datastruct/kvldskey.h ../../libcperciva/util/ctassert.h ../../libcperciva/util/monoclock.h ../../lib/proto_kvlds/proto_kvlds.h ../../lib/netbuf/netbuf.h ../../lib/wire/wire.h ../../libcperciva/util/sock.h ../../libcperciva/util/warnp.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c main.c -o main.o
elasticarray.o: ../../libcperciva/datastruct/elasticarray.c ../../libcperciva/datastruct/elasticarray.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/datastruct/elasticarray.c -o elasticarray.o
ptrheap.o: ../../libcperciva/datastruct/ptrheap.c ../../libcperciva/datastruct/elasticarray.h ../../libcperciva/datastruct/ptrheap.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/datastruct/ptrheap.c -o ptrheap.o
timerqueue.o: ../../libcperciva/datastruct/timerqueue.c ../../libcperciva/datastruct/ptrheap.h ../../libcperciva/datastruct/timerqueue.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/datastruct/timerqueue.c -o timerqueue.o
elasticqueue.o: ../../libcperciva/datastruct/elasticqueue.c ../../libcperciva/datastruct/elasticarray.h ../../libcperciva/datastruct/elasticqueue.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/datastruct/elasticqueue.c -o elasticqueue.o
seqptrmap.o: ../../libcperciva/datastruct/seqptrmap.c ../../libcperciva/datastruct/elasticqueue.h ../../libcperciva/datastruct/seqptrmap.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/datastruct/seqptrmap.c -o seqptrmap.o
kvldskey.o: ../../lib/datastruct/kvldskey.c ../../lib/datastruct/kvldskey.h ../../libcperciva/util/ctassert.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../lib/datastruct/kvldskey.c -o kvldskey.o
monoclock.o: ../../libcperciva/util/monoclock.c ../../libcperciva/util/warnp.h ../../libcperciva/util/monoclock.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/util/monoclock.c -o monoclock.o
sock.o: ../../libcperciva/util/sock.c ../../libcperciva/util/imalloc.h ../../libcperciva/util/warnp.h ../../libcperciva/util/sock.h ../../libcperciva/util/sock_internal.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/util/sock.c -o sock.o
warnp.o: ../../libcperciva/util/warnp.c ../../libcperciva/util/warnp.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/util/warnp.c -o warnp.o
crc32c.o: ../../libcperciva/alg/crc32c.c ../../libcperciva/alg/crc32c.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/alg/crc32c.c -o crc32c.o
events_immediate.o: ../../libcperciva/events/events_immediate.c ../../libcperciva/datastruct/mpool.h ../../libcperciva/events/events.h ../../libcperciva/events/events_internal.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/events/events_immediate.c -o events_immediate.o
events_network.o: ../../libcperciva/events/events_network.c ../../libcperciva/datastruct/elasticarray.h ../../libcperciva/util/warnp.h ../../libcperciva/events/events.h ../../libcperciva/events/events_internal.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/events/events_network.c -o events_network.o
events_network_selectstats.o: ../../libcperciva/events/events_network_selectstats.c ../../libcperciva/util/monoclock.h ../../libcperciva/events/events.h ../../libcperciva/events/events_internal.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/events/events_network_selectstats.c -o events_network_selectstats.o
events_timer.o: ../../libcperciva/events/events_timer.c ../../libcperciva/util/monoclock.h ../../libcperciva/datastruct/timerqueue.h ../../libcperciva/events/events.h ../../libcperciva/events/events_internal.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/events/events_timer.c -o events_timer.o
events.o: ../../libcperciva/events/events.c ../../libcperciva/datastruct/mpool.h ../../libcperciva/events/events.h ../../libcperciva/events/events_internal.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/events/events.c -o events.o
network_read.o: ../../libcperciva/network/network_read.c ../../libcperciva/events/events.h ../../libcperciva/datastruct/mpool.h ../../libcperciva/network/network.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/network/network_read.c -o network_read.o
network_write.o: ../../libcperciva/network/network_write.c ../../libcperciva/events/events.h ../../libcperciva/datastruct/mpool.h ../../libcperciva/util/warnp.h ../../libcperciva/network/network.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../libcperciva/network/network_write.c -o network_write.o
netbuf_read.o: ../../lib/netbuf/netbuf_read.c ../../libcperciva/events/events.h ../../libcperciva/network/network.h ../../lib/netbuf/netbuf.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../lib/netbuf/netbuf_read.c -o netbuf_read.o
netbuf_write.o: ../../lib/netbuf/netbuf_write.c ../../libcperciva/network/network.h ../../libcperciva/util/warnp.h ../../lib/netbuf/netbuf.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../lib/netbuf/netbuf_write.c -o netbuf_write.o
wire_packet.o: ../../lib/wire/wire_packet.c ../../libcperciva/datastruct/mpool.h ../../lib/wire/wire.h ../../lib/netbuf/netbuf.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../lib/wire/wire_packet.c -o wire_packet.o
wire_readpacket.o: ../../lib/wire/wire_readpacket.c ../../libcperciva/alg/crc32c.h ../../libcperciva/events/events.h ../../libcperciva/datastruct/mpool.h ../../lib/netbuf/netbuf.h ../../libcperciva/util/sysendian.h ../../libcperciva/util/warnp.h ../../lib/wire/wire.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../lib/wire/wire_readpacket.c -o wire_readpacket.o
wire_writepacket.o: ../../lib/wire/wire_writepacket.c ../../libcperciva/alg/crc32c.h ../../lib/netbuf/netbuf.h ../../libcperciva/util/sysendian.h ../../lib/wire/wire.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../lib/wire/wire_writepacket.c -o wire_writepacket.o
wire_requestqueue.o: ../../lib/wire/wire_requestqueue.c ../../libcperciva/events/events.h ../../libcperciva/datastruct/mpool.h ../../lib/netbuf/netbuf.h ../../libcperciva/datastruct/seqptrmap.h ../../libcperciva/util/warnp.h ../../lib/wire/wire.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../lib/wire/wire_requestqueue.c -o wire_requestqueue.o
proto_kvlds_client.o: ../../lib/proto_kvlds/proto_kvlds_client.c ../../libcperciva/events/events.h ../../libcperciva/util/imalloc.h ../../libcperciva/datastruct/mpool.h ../../libcperciva/util/sysendian.h ../../libcperciva/util/warnp.h ../../lib/wire/wire.h ../../lib/netbuf/netbuf.h ../../lib/proto_kvlds/proto_kvlds.h ../../lib/datastruct/kvldskey.h ../../libcperciva/util/ctassert.h
	${CC} ${CFLAGS} ${CFLAGS_POSIX} -D_POSIX_C_SOURCE=200809L -D_XOPEN_SOURCE=700  -I.. ${IDIRS} -c ../../lib/proto_kvlds/proto_kvlds_client.c -o proto_kvlds_client.o
