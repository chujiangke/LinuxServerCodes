# From "Thinking in C++, 2nd Edition, Volume 1, 
# Annotated Solutions Guide" by Chuck Allison
# At http://www.BruceEckel.com
# (c)2001 MindView Inc. Copyright notice in Copyright.txt
# Automatically-generated MAKEFILE 
# For examples in directory .\S10
# Invoke with: make

CPP = g++

OFLAGS = -c
EXEFLAG = -o
OBJEXT = obj
#自定义三个后缀规则 .cpp .obj .exe
.SUFFIXES : .cpp .$(OBJEXT) .exe
#.obj 的依赖对应的 .cpp 文件, 也可以理解为 根据.cpp 文件生成.obj 文件。
.cpp.$(OBJEXT) :
	$(CPP) $(OFLAGS) $<
#同理.exe依赖.cpp文件,也可以理解为根据.cpp 文件生成.exe文件。
.cpp.exe :
	$(CPP) $< $(EXEFLAG) $@

all:  \
	5-1byteorder.exe \
	5-3testlisten.exe \
	5-5testaccept.exe \
	5-6oobsend.exe \
	5-7oobrecv.exe \
	5-9reuse_address.exe \
	5-10set_send_buffer.exe

clean:
ifeq ($(notdir $(SHELL)),COMMAND.COM)
	del *.obj
	del *.exe
	del *.tds
	del *.o
else
	rm -f *.o *.obj *.exe *.tds
endif

5-1byteorder.exe: 5-1byteorder.cpp
5-3testlisten.exe: 5-3testlisten.cpp
5-5testaccept.exe: 5-5testaccept.cpp
5-6oobsend.exe: 5-6oobsend.cpp
5-7oobrecv.exe: 5-7oobrecv.cpp
5-9reuse_address.exe: 5-9reuse_address.cpp
5-10set_send_buffer.exe: 5-10set_send_buffer.cpp

#UnnamedUnique.$(OBJEXT): UnnamedUnique.cpp
#Exercise7.exe: CharArray.$(OBJEXT) Exercise7.$(OBJEXT)
#	$(CPP) $(CPPFLAGS) $(EXEFLAG)Exercise7.exe Exercise7.$(OBJEXT) CharArray.$(OBJEXT)

#Exercise7.$(OBJEXT): Exercise7.cpp
#FieldAccessors.exe: FieldAccessors.cpp
