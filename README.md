# encfs-java

- Changed BlockCrypto.java
  volume.getBlockCipher() 
    to 
  BlockCrypto.newBlockCipher()

- Changed StreamCrypto.java
  volume.getStreamCipher()
    to 
  StreamCrypto.newStreamCipher()
  
- Chnaged  
  Arrays.copyOf()
    to
  EncFSUtil.copyOf()
  
- Chnaged  
  Arrays.copyOfRange()
    to
  EncFSUtil.copyOfRange()

- Added synchronized to mothods in EncFSCrypto.java

- And some other tiny changes.
