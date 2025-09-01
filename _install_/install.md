# Created
tar czvf - Homebrew-4.3.0.pkg |split -b 25m - brew-4.3.0.pkg.tgz.


# Recombined 
cat brew-4.3.0.pkg.tgz.a* | tar xzvf -
