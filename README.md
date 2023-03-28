# dependencies
Android Development Dependencies

# For view binding 
add following lines of code to android {} <br>
<pre>
buildFeatures {
  viewBinding = true
 }
</pre>

# For Live data and View Model ( dependency level ) 
<pre>
  def lifecycle_version = "2.4.0"
  implementation "androidx.lifecycle:lifecycle-viewmodel:$lifecycle_version"
  implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:$lifecycle_version"
</pre>

# For navigation ( jetpack ) (New with Nav graph)

<pre>
  <a target="_blank" href="https://developer.android.com/jetpack/androidx/releases/navigation">Click the Developer docs link </a>
</pre>
