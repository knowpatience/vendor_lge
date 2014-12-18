vendor_lge
==========

This project adds the Lollipop 5.0 vendor blobs for hammerhead and a customized gapps package. 

To use these packages in a build, add the following lines to your local_manifest.xml:

    <manifest>
  
      <remote name="github" fetch="https://github.com/" />
  
      <project path="vendor/google" name="knowpatience/vendor_gapps" remote="github" revision="master"/>
      <project path="vendor/lge" name="knowpatience/vendor_lge" remote="github" revision="master"/>
      <project path="vendor/bcom" name="knowpatience/vendor_bcom" remote="github" revision="master"/>
      <project path="vendor/qcom" name="knowpatience/vendor_qcom" remote="github" revision="master"/>
  
    </manifest>
