<h1>Linux Command List</h1>

<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>ls</td>
    <td>List directory contents</td>
  </tr>
  <tr>
    <td>cd</td>
    <td>Change directory</td>
  </tr>
  <tr>
    <td>pwd</td>
    <td>Print working directory</td>
  </tr>
  <tr>
    <td>mkdir</td>
    <td>Create a new directory</td>
  </tr>
  <tr>
    <td>rm</td>
    <td>Remove files or directories</td>
  </tr>
  <tr>
    <td>cp</td>
    <td>Copy files and directories</td>
  </tr>
  <tr>
    <td>mv</td>
    <td>Move or rename files and directories</td>
  </tr>
  <tr>
    <td>touch</td>
    <td>Create an empty file</td>
  </tr>
  <tr>
    <td>cat</td>
    <td>Concatenate and display file contents</td>
  </tr>
  <tr>
    <td>grep</td>
    <td>Search text patterns in files</td>
  </tr>
  <tr>
    <td>chmod</td>
    <td>Change file permissions</td>
  </tr>
  <tr>
    <td>chown</td>
    <td>Change file ownership</td>
  </tr>
  <tr>
    <td>ssh</td>
    <td>Secure shell remote login</td>
  </tr>
  <tr>
    <td>sudo</td>
    <td>Execute a command as a superuser</td>
  </tr>
</table>
<h1>ls Command with Key Options</h1>

<table>
  <tr>
    <th>Option</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>-a</td>
    <td>Show hidden files</td>
  </tr>
  <tr>
    <td>-l</td>
    <td>Long format: display detailed file information</td>
  </tr>
  <tr>
    <td>-h</td>
    <td>Human-readable sizes</td>
  </tr>
  <tr>
    <td>-R</td>
    <td>Recursively list subdirectories</td>
  </tr>
  <tr>
    <td>-t</td>
    <td>Sort by modification time</td>
  </tr>
  <tr>
    <td>-S</td>
    <td>Sort by file size</td>
  </tr>
  <tr>
    <td>-r</td>
    <td>Reverse order</td>
  </tr>
  <tr>
    <td>-G</td>
    <td>Colorize output</td>
  </tr>
  <tr>
    <td>-d</td>
    <td>List directories themselves, not their contents</td>
  </tr>
</table>
<h1>cd Command</h1>

<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>cd</td>
    <td>Change directory to the user's home directory</td>
  </tr>
  <tr>
    <td>cd [directory]</td>
    <td>Change directory to the specified directory</td>
  </tr>
  <tr>
    <td>cd ~</td>
    <td>Change directory to the user's home directory</td>
  </tr>
  <tr>
    <td>cd ..</td>
    <td>Change directory to the parent directory</td>
  </tr>
  <tr>
    <td>cd -</td>
    <td>Change directory to the previous directory</td>
  </tr>
</table>
<h1>mv Command</h1>

<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>mv [source] [destination]</td>
    <td>Move or rename a file or directory</td>
  </tr>
  <tr>
    <td>mv [file1] [file2] [directory]</td>
    <td>Move multiple files to a directory</td>
  </tr>
  <tr>
    <td>mv -i [source] [destination]</td>
    <td>Move or rename a file or directory with interactive confirmation</td>
  </tr>
  <tr>
    <td>mv -u [source] [destination]</td>
    <td>Move or rename a file or directory only if the destination file is newer</td>
  </tr>
  <tr>
    <td>mv -v [source] [destination]</td>
    <td>Move or rename a file or directory, displaying verbose output</td>
  </tr>
</table>

<h1>touch Command</h1>

<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>touch [file1] [file2] ...</td>
    <td>Create one or more empty files</td>
  </tr>
  <tr>
    <td>touch -a [file]</td>
    <td>Change the access time of a file to the current time</td>
  </tr>
  <tr>
    <td>touch -m [file]</td>
    <td>Change the modification time of a file to the current time</td>
  </tr>
  <tr>
    <td>touch -c [file]</td>
    <td>Do not create a file if it doesn't exist</td>
  </tr>
  <tr>
    <td>touch -r [reference_file] [file]</td>
    <td>Set the access and modification times of a file to match those of a reference file</td>
  </tr>
</table>

<h1>cat Command</h1>

<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>cat [file1] [file2] ...</td>
    <td>Concatenate and display the contents of one or more files</td>
  </tr>
  <tr>
    <td>cat -n [file]</td>
    <td>Display the contents of a file with line numbers</td>
  </tr>
  <tr>
    <td>cat -b [file]</td>
    <td>Display the contents of a file with line numbers, but only for non-blank lines</td>
  </tr>
  <tr>
    <td>cat -s [file]</td>
    <td>Squeeze multiple consecutive empty lines into a single empty line</td>
  </tr>
  <tr>
    <td>cat -E [file]</td>
    <td>Display the contents of a file with a dollar sign ($) at the end of each line</td>
  </tr>
</table>



