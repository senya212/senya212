program Project1;
{$APPTYPE CONSOLE}
{$R *.res}
uses
  System.SysUtils;
var
  a:array[1..10] of byte;
  s,i:byte;
begin
    s:=0;
    for i:=1 to 10 do
    write(a[i],' ');
    read;
    writeln;
    for i:=1 to 10 do
    begin if i mod 2=0 then
    s:=s+a[i];
    end;
writeln('summa = ',s); readln;
end.
