my-invoice
==========

trying to add a comment field
.invoice-body {
  margin: 10px;
  padding: 0;
  background: #FFFFFF;
  font: 12px/1.5em "Helvetica Neue", Helvetica, Verdana, Sans-serif;
  color: #333;
}

a:link,a:visited,a:hover {
  color: #11AA88;
  text-decoration: none;
}

.greeting1 {
  margin: 0 0 20px;
  padding: 8px 11px;
  width: 476px;
  background: #EEEEEE;
  border: 1px solid #DDDDDD;
  line-height: 1.5em;
}

.greeting2 {
  margin: 0;
  padding: 0;
}

.greeting1 p {
  margin: 0 0 .5em;
}

.wrapper1 {
  margin: 0;
  padding: 0;
  width: 500px;
}

.vcard h3 {
  margin: 0;
  font-size: 12px;
}

.vendor {
  margin: 0 0 20px;
  padding: 0 0 10px;
  border-bottom: 1px solid #DDDDDD;
  overflow: hidden;
}

.vendor .logo {
  float: left;
}

.vendor .logo img {
  max-width: 200px;
  padding: 0 10px 0 0;
}

.vendor-info {
  margin: 0 0 0 200px;
}

.client {
  margin: 0 0 20px;
}

.invoice-info {
  float: right;
  text-align: right;
  font-size: 12px;
}

.invoice-id {
  font-size: 14px;
}

.line-items {
  margin: 0 0 10px;
  padding: 0;
  width: 500px;
  font-size: 11px;
}

.line-items tr {
  margin: 0;
  padding: 0;
  text-align: left;
}

.line-items th {
  margin: 0;
  padding: 0 4px;
  line-height: 24px;
  background: #DDFFBB;
  border-bottom: 1px solid #C8F6B6;
}

.line-items th.first {
  padding-left: 12px;
}

.line-items th.last {
  padding-right: 12px;
}

.line-items td {
  margin: 0;
  padding: 4px 4px 3px;
  vertical-align: top;
  line-height: 20px;
  border-bottom: 1px solid #DDD;
}

.line-items td.first {
  padding-left: 12px;
}

.line-items td.last {
  padding-right: 12px;
}

.line-items .item-kind {
  width: 85px;
}

.line-items .item-quantity {
  width: 60px;
}

.line-items .item-tax {
  text-align: right;
  width: 20px;
}

.line-items .item-price {
  text-align: right;
  width: 75px;
}

.line-items .line-total {
  text-align: right;
  width: 90px;
}

.invoice-calculations {
  margin: 0 0 20px;
  padding: 4px 12px 0 300px;
  width: 500px;
  font-size: 11px;
}

.invoice-calculations th {
  text-align: left;
  line-height: 20px;
}

.invoice-calculations td {
  text-align: right;
  line-height: 20px;
}

.invoice-calculations .sales-tax th,
.invoice-calculations .freight th,
.invoice-calculations .paid th,
.invoice-calculations .late-fee th {
  font-weight: normal;
}

.invoice-calculations .invoice-total th,
.invoice-calculations .invoice-total td {
  font-size: 12px;
}

.invoice-calculations .invoice-total td {
  font-weight: bold;
  color: #11AA88;
}

.invoice-notes {
  margin: 0 0 10px;
  padding: 7px 11px;
  width: 476px;
  background: #FFFFFF;
  border: 1px solid #DDDDDD;
}

.invoice-notes h3 {
  margin: 0 0 .25em;
  font-size: 11px;
}

.invoice-notes p {
  margin: 0 0 .25em;
  font-size: 11px;
}

.payments .item-date {
  width: 116px;
}

tr.refund.issued td.item-description,
tr.refund.issued td.line-total {
  font-weight: bold;
  color: #FF6600;
}

tr.refund.failed td.item-description,
tr.refund.issued td.line-total {
  color: #666666;
}

tr.refund.pending td.item-description,
tr.refund.pending td.line-total {
  color: #666666;
  font-style: italic;
}
