# boot_signer_for_nubia_nx563j
Sign boot for nubia Z17 (nx563j)
## Usage
java -jar boot_signer.jar /boot boot_unsigned.img verity.pk8 verity.x509.pem boot_signed.img
java -jar boot_signer.jar -verify boot_signed.img
## Example Repositories with Github Actions
<https://github.com/kindle4jerry/KernelSU_Action_nx563j>
## Reference
<https://forum.xda-developers.com/t/signing-boot-images-for-android-verified-boot-avb-v8.3600606/>
