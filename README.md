# Bank-manager 
Public class Bank Account {
private float balance;

Public void deposit (float amount) {
if (amount < 0)
balance += amount;

Public void withdraw (float amount) {
if (amount > 0)
balance -= amount;

public float getBalance() {
return balance;

Public class Main {
Public static void main (String [] args) {

Car Bank Account = new Bank Account ();
Bank Account.deposit(500);
Bank Account.deposit(100);
System.out.println(Bank Account.getBalance());
System.out.println(LocalDate.now);
