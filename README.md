# email-checker
Confirm existence of e-mail address.

## Requirements
<dl>
  <dt>Perl</dt>
  <dt>Swaks - Swiss Army Knife for SMTP</dt>
  <dd>http://www.jetmore.org/john/code/swaks/</dd>
</dl>

## Usage Example
```shellscript
% cat email-list.txt
% aaa@example.com
% bbb@example.com

% sh email-checker email-list.txt
"aaa@example.com","true","ok"
"bbb@example.com","false","24"
```

## Swaks - EXIT CODES
```shellscript
% perldoc swaks
```
