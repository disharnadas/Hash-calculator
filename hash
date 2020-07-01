fl=input("enter file name(file_name.format)\n")
try:
    fhand=open(fl)
    x=fhand.read()
    print("content:\n",x)
    import hashlib
    mod=input("Choose mode: 1.SHA1 2.MD5 3.SHA224 4.SHA256 5.SHA384 6.SHA512\n")

    if int(mod)==1:

        m=hashlib.sha1()
        y=x.encode('utf-8')
        z=y.decode('utf-8')
        m.update(y)
        p=m.hexdigest()
        print("calculated hash:\n",p)
        print("hash decode:\n",z)
    else :
        if int(mod)==2:
            m=hashlib.md5()
            y=x.encode('utf-8')
            z=y.decode('utf-8')
            m.update(y)
            p=m.hexdigest()
            print("calculated hash:\n",p)
            print("hash decode:\n",z)
    
        else:
            if int(mod)==3:
                m=hashlib.sha224()
                y=x.encode('utf-8')
                z=y.decode('utf-8')
                m.update(y)
                p=m.hexdigest()
                print("calculated hash:\n",p)
                print("hash decode:\n",z)
            else:
                if int(mod)==4:
                    m=hashlib.sha256()
                    y=x.encode('utf-8')
                    z=y.decode('utf-8')
                    m.update(y)
                    p=m.hexdigest()
                    print("calculated hash:\n",p)
                    print("hash decode:\n",z)
                    
                else:
                    if int(mod)==5:
                        m=hashlib.sha384()
                        y=x.encode('utf-8')
                        z=y.decode('utf-8')
                        m.update(y)
                        p=m.hexdigest()
                        print("calculated hash:\n",p)
                        print("hash decode:\n",z)
                        
                    else:
                        if int(mod)==6:
                            m=hashlib.sha512()
                            y=x.encode('utf-8')
                            z=y.decode('utf-8')
                            m.update(y)
                            p=m.hexdigest()
                            print("calculated hash:\n",p)
                            print("hash decode:\n",z)
                        else:
                
                                print("Wrong Input")
            
    
except:
    print("File not found:",fl)
