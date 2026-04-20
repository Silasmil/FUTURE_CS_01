# Phishing Email Analysis Report

**Analyst:** Milton Silas  
**Date:** April 20, 2026  
**Task:** Phishing Detection & Awareness System

## Executive Summary

Four email samples were analyzed. **Three were confirmed phishing**, and **one was legitimate**. This report documents indicators and provides prevention guidelines.

---

## Analysis Results

| Sample | Sender Domain | Key Red Flags | Classification |
|--------|---------------|---------------|----------------|
| PayPal | paypal.com.verify-account.net | Fake domain, urgent threat | 🔴 PHISHING |
| DHL | dhl-delivery.com | Fake domain, tracking scam | 🔴 PHISHING |
| Microsoft | microsoft-security.net | Fake domain, fear tactic | 🔴 PHISHING |
| GitHub | github.com | Real domain, personalized | 🟢 SAFE |

---

## Detailed Findings

### Sample 1: PayPal Account Alert 🔴 PHISHING

**Indicators:**
- ❌ Fake sender: paypal.com.verify-account.net
- ❌ Generic greeting: "Dear Customer"
- ❌ Urgent threat: "Failure will result in account closure"
- ❌ Suspicious link: paypal.verify-account.net

**Why it's phishing:** Real PayPal emails come from @paypal.com only.

---

### Sample 2: DHL Delivery Scam 🔴 PHISHING

**Indicators:**
- ❌ Fake sender: dhl-delivery.com (real is dhl.com)
- ❌ 48-hour deadline pressure
- ❌ Suspicious tracking link

**Why it's phishing:** DHL uses dhl.com for all official communications.

---

### Sample 3: Microsoft Security Alert 🔴 PHISHING

**Indicators:**
- ❌ Fake sender: microsoft-security.net (real is microsoft.com)
- ❌ Fear tactic: claims login from Russia
- ❌ Fake device: iPhone 12

**Why it's phishing:** Microsoft sends alerts from @microsoft.com only.

---

### Sample 4: GitHub Security Alert 🟢 SAFE

**Indicators:**
- ✅ Real sender: github.com
- ✅ Personalized: "Hi Milton Silas"
- ✅ Accurate details: Kali Linux, Nairobi
- ✅ No urgency: "If this was you, ignore"

**Why it's legitimate:** The email comes from real GitHub domain with accurate information.

---

## Phishing Indicators Checklist

### Red Flags to Watch For:
- [ ] Spoofed or fake domain
- [ ] Generic greeting ("Dear Customer")
- [ ] Urgent/threatening language
- [ ] Suspicious links (hover to check)
- [ ] Requests for personal information
- [ ] Poor grammar or spelling
- [ ] Unexpected attachments

---

## Prevention Guidelines

### DO's ✅
1. Verify sender email address
2. Hover over links before clicking
3. Type URLs directly into browser
4. Enable MFA on all accounts
5. Report suspicious emails to IT

### DON'Ts ❌
1. Click links in unexpected emails
2. Download unknown attachments
3. Reply with personal information
4. Panic to urgent demands
5. Ignore browser security warnings

---

## Incident Response

If you receive a phishing email:

1. **STOP** - Don't click anything
2. **REPORT** - Forward to security team
3. **DELETE** - Remove from inbox
4. **SCAN** - Run antivirus if clicked
5. **CHANGE** - Update passwords if credentials entered

---

## Conclusion

Phishing remains the #1 cyber threat because it targets humans, not technology. Regular training and awareness reduce successful phishing attacks by up to 70%.

---
**Prepared for:** Future Interns - Cybersecurity Track
**Prepared by:** Milton Silas
**Date:** April 20, 2026
