terraform {
  required_providers {
    pingdom = {
      source = "russellcardullo/pingdom"
      version = "1.1.2"
    }
  }
}

variable "pingdom_user" {raufrustam.ov@outlook.com}
variable "pingdom_password" {Nse54b!5!}
variable "pingdom_api_key" {bbdOSapWP8EdMZF6t4nno0G38kRLFr3OW6d9BajmD6y4t0XvvS2fjs_C1uq06bBtlaFHZXQ}
variable "pingdom_account_email" {} # Optional: only required for multi-user accounts

provider "pingdom" {
    user = "${var.pingdom_user}"
    password = "${var.pingdom_password}"
    api_key = "${var.pingdom_api_key}"
    account_email = "${var.pingdom_account_email}" # Optional: only required for multi-user accounts
}
