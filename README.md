# ALIGNEDLAYER PUBLIC PROOF TASK  

<img width="908" alt="image" src="https://github.com/raghav353/Alignedlayer-testnet-proof/assets/151916837/088cc7a9-8763-4c51-9010-0dcb216deaa6">


## Getting Srtarted 

```
sudo apt update -y
sudo apt upgrade -y
```

### Install curl 
```
sudo apt-get install curl -y
```

### Download ALignedProof 
<img width="806" alt="image" src="https://github.com/raghav353/Alignedlayer-testnet-proof/assets/151916837/2bc4977d-7edf-405f-ace7-68273c01d4e9">

```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/install_aligned.sh | bash
```

```
source /root/.bashrc
```


### Download an example SP1 proof file with it's ELF file 
<img width="805" alt="image" src="https://github.com/raghav353/Alignedlayer-testnet-proof/assets/151916837/57d85196-77da-4e8e-95bc-3f2f8d721d51">


```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/get_proof_test_files.sh | bash
```


### Sending proof 

<img width="812" alt="image" src="https://github.com/raghav353/Alignedlayer-testnet-proof/assets/151916837/63dcd1a9-4613-4aee-949a-7302b4680537">

```
rm -rf ~/aligned_verification_data/ &&
aligned submit \
--proving_system SP1 \
--proof ~/.aligned/test_files/sp1_fibonacci.proof \
--vm_program ~/.aligned/test_files/sp1_fibonacci-elf \
--aligned_verification_data_path ~/aligned_verification_data \
--conn wss://batcher.alignedlayer.com
```

use this code to get the log you will screenshot for your X post
```
aligned verify-proof-onchain \
--aligned-verification-data ~/aligned_verification_data/*.json \
--rpc https://ethereum-holesky-rpc.publicnode.com \
--chain holesky
```


Use the explorer link in CMD to check if verified and you'll also see below image. 
<img width="805" alt="image" src="https://github.com/raghav353/Alignedlayer-testnet-proof/assets/151916837/259133d9-e831-4817-af15-b09fd610dcb4">

<img width="958" alt="image" src="https://github.com/raghav353/Alignedlayer-testnet-proof/assets/151916837/e78b557f-2c8e-459d-9a7b-edd8cee815b0">



-------------
----------------------
### Tweet exactly as screenshot and Submit Proof in Dscord 

<img width="459" alt="image" src="https://github.com/raghav353/Alignedlayer-testnet-proof/assets/151916837/c9a62ca8-6c64-4835-be7a-282f44fc124c">



--------------------------
### Submit in Discord 
<img width="901" alt="image" src="https://github.com/raghav353/Alignedlayer-testnet-proof/assets/151916837/e5c74a22-20a6-4b11-9e24-095465341ba6">


# JOIN DISCORD FROM PROFILE 
https://linktr.ee/AlignedLayer




