# python-9
file format
# readindg the data from file
file=open('sai.txt','r')
data=file.read()
print("file data in groups.txt:",data)
file.close()

#writiing the data to file
f=open('exp.txt','w')
f.write("my name is sai krishna.....")
f.close()

#appending the data to file
f=open('exp.txt','a')
f.write("iam from vuyyuru")
f.close()

