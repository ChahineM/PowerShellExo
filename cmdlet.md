## Challenge cmdlet

cp → **Copy-Item**  
rm → **Remove-Item**  
cd → **Set-Location**  
man → **Get-Help**  
history → **Get-History**  
alias → **Get-Alias** ou **Set-Alias**  
cat → **Get-Content**  

PS /home/chahine> Get-Command copy      

CommandType     Name                                               Version    Source
-----------     ----                                               -------    ------
Alias           copy -> Copy-Item                                             

PS /home/chahine> Get-Command *copy*

CommandType     Name                                               Version    Source
-----------     ----                                               -------    ------
Alias           copy -> Copy-Item                                             
Cmdlet          Copy-Item                                          7.0.0.0    Microso…
Cmdlet          Copy-ItemProperty                                  7.0.0.0    Microso…
Application     debconf-copydb                                     0.0.0.0    /usr/bi…
Application     debconf-copydb                                     0.0.0.0    /bin/de…
Application     objcopy                                            0.0.0.0    /usr/bi…
Application     objcopy                                            0.0.0.0    /bin/ob…
Application     ssh-copy-id                                        0.0.0.0    /usr/bi…
Application     ssh-copy-id                                        0.0.0.0    /bin/ss…
Application     x86_64-linux-gnu-objcopy                           0.0.0.0    /usr/bi…
Application     x86_64-linux-gnu-objcopy                           0.0.0.0    /bin/x8…

PS /home/chahine> Get-Command *remove*

CommandType     Name                                               Version    Source
-----------     ----                                               -------    ------
Cmdlet          Remove-Alias                                       7.0.0.0    Microso…
Cmdlet          Remove-Event                                       7.0.0.0    Microso…
Cmdlet          Remove-Item                                        7.0.0.0    Microso…
Cmdlet          Remove-ItemProperty                                7.0.0.0    Microso…
Cmdlet          Remove-Job                                         7.5.0.500  Microso…
Cmdlet          Remove-Module                                      7.5.0.500  Microso…
Cmdlet          Remove-PSBreakpoint                                7.0.0.0    Microso…
Cmdlet          Remove-PSDrive                                     7.0.0.0    Microso…
Cmdlet          Remove-PSReadLineKeyHandler                        2.4.0      PSReadL…
Cmdlet          Remove-PSSession                                   7.5.0.500  Microso…
Cmdlet          Remove-TypeData                                    7.0.0.0    Microso…
Cmdlet          Remove-Variable                                    7.0.0.0    Microso…
Application     aa-remove-unknown                                  0.0.0.0    /usr/sb…
Application     aa-remove-unknown                                  0.0.0.0    /sbin/a…
Application     remove-default-ispell                              0.0.0.0    /usr/sb…
Application     remove-default-ispell                              0.0.0.0    /sbin/r…
Application     remove-default-wordlist                            0.0.0.0    /usr/sb…
Application     remove-default-wordlist                            0.0.0.0    /sbin/r…
Application     remove-shell                                       0.0.0.0    /usr/sb…
Application     remove-shell                                       0.0.0.0    /sbin/r…

PS /home/chahine> Get-Command *location*

CommandType     Name                                               Version    Source
-----------     ----                                               -------    ------
Cmdlet          Get-Location                                       7.0.0.0    Microso…
Cmdlet          Pop-Location                                       7.0.0.0    Microso…
Cmdlet          Push-Location                                      7.0.0.0    Microso…
Cmdlet          Set-Location                                       7.0.0.0    Microso…

PS /home/chahine> Get-Command *help*    

CommandType     Name                                               Version    Source
-----------     ----                                               -------    ------
Function        help                                                          
Cmdlet          Get-Help                                           7.5.0.500  Microso…
Cmdlet          Save-Help                                          7.5.0.500  Microso…
Cmdlet          Update-Help                                        7.5.0.500  Microso…
Application     deb-systemd-helper                                 0.0.0.0    /usr/bi…
Application     deb-systemd-helper                                 0.0.0.0    /bin/de…
Application     dpkg-maintscript-helper                            0.0.0.0    /usr/bi…
Application     dpkg-maintscript-helper                            0.0.0.0    /bin/dp…
Application     gnome-help                                         0.0.0.0    /usr/bi…
Application     gnome-help                                         0.0.0.0    /bin/gn…
Application     helpztags                                          0.0.0.0    /usr/bi…
Application     helpztags                                          0.0.0.0    /bin/he…
Application     mkhomedir_helper                                   0.0.0.0    /usr/sb…
Application     mkhomedir_helper                                   0.0.0.0    /sbin/m…
Application     pam_namespace_helper                               0.0.0.0    /usr/sb…
Application     pam_namespace_helper                               0.0.0.0    /sbin/p…
Application     pwhistory_helper                                   0.0.0.0    /usr/sb…
Application     pwhistory_helper                                   0.0.0.0    /sbin/p…
Application     tracker3-help                                      0.0.0.0    /usr/bi…
Application     tracker3-help                                      0.0.0.0    /bin/tr…

PS /home/chahine> Get-Command *history*

CommandType     Name                                               Version    Source
-----------     ----                                               -------    ------
Alias           history -> Get-History                                        
Cmdlet          Add-History                                        7.5.0.500  Microso…
Cmdlet          Clear-History                                      7.5.0.500  Microso…
Cmdlet          Get-History                                        7.5.0.500  Microso…
Cmdlet          Invoke-History                                     7.5.0.500  Microso…
Application     pwhistory_helper                                   0.0.0.0    /usr/sb…
Application     pwhistory_helper                                   0.0.0.0    /sbin/p…

PS /home/chahine> Get-Command *alias*  

CommandType     Name                                               Version    Source
-----------     ----                                               -------    ------
Cmdlet          Export-Alias                                       7.0.0.0    Microso…
Cmdlet          Get-Alias                                          7.0.0.0    Microso…
Cmdlet          Import-Alias                                       7.0.0.0    Microso…
Cmdlet          New-Alias                                          7.0.0.0    Microso…
Cmdlet          Remove-Alias                                       7.0.0.0    Microso…
Cmdlet          Set-Alias                                          7.0.0.0    Microso…
Application     update-fonts-alias                                 0.0.0.0    /usr/sb…
Application     update-fonts-alias                                 0.0.0.0    /sbin/u…

PS /home/chahine> Get-Command *content*

CommandType     Name                                               Version    Source
-----------     ----                                               -------    ------
Cmdlet          Add-Content                                        7.0.0.0    Microso…
Cmdlet          Clear-Content                                      7.0.0.0    Microso…
Cmdlet          Get-Content                                        7.0.0.0    Microso…
Cmdlet          Set-Content                                        7.0.0.0    Microso…

PS /home/chahine> ^C
