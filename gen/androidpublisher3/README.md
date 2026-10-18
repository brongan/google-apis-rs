<!---
DO NOT EDIT !
This file was generated automatically from 'src/generator/templates/api/README.md.mako'
DO NOT EDIT !
-->
The `google-androidpublisher3` library allows access to all features of the *Google Android Publisher* service.

This documentation was generated from *Android Publisher* crate version *7.0.0+20251216*, where *20251216* is the exact revision of the *androidpublisher:v3* schema built by the [mako](http://www.makotemplates.org/) code generator *v7.0.0*.

Everything else about the *Android Publisher* *v3* API can be found at the
[official documentation site](https://developers.google.com/android-publisher).
# Features

Handle the following *Resources* with ease from the central [hub](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.AndroidPublisher.html) ...

* applications
 * [*data safety*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ApplicationDataSafetyCall.html), [*device tier configs create*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ApplicationDeviceTierConfigCreateCall.html), [*device tier configs get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ApplicationDeviceTierConfigGetCall.html) and [*device tier configs list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ApplicationDeviceTierConfigListCall.html)
* apprecovery
 * [*add targeting*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ApprecoveryAddTargetingCall.html), [*cancel*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ApprecoveryCancelCall.html), [*create*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ApprecoveryCreateCall.html), [*deploy*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ApprecoveryDeployCall.html) and [*list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ApprecoveryListCall.html)
* edits
 * [*apks addexternallyhosted*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditApkAddexternallyhostedCall.html), [*apks list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditApkListCall.html), [*apks upload*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditApkUploadCall.html), [*bundles list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditBundleListCall.html), [*bundles upload*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditBundleUploadCall.html), [*commit*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditCommitCall.html), [*countryavailability get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditCountryavailabilityGetCall.html), [*delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditDeleteCall.html), [*deobfuscationfiles upload*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditDeobfuscationfileUploadCall.html), [*details get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditDetailGetCall.html), [*details patch*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditDetailPatchCall.html), [*details update*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditDetailUpdateCall.html), [*expansionfiles get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditExpansionfileGetCall.html), [*expansionfiles patch*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditExpansionfilePatchCall.html), [*expansionfiles update*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditExpansionfileUpdateCall.html), [*expansionfiles upload*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditExpansionfileUploadCall.html), [*get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditGetCall.html), [*images delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditImageDeleteCall.html), [*images deleteall*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditImageDeleteallCall.html), [*images list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditImageListCall.html), [*images upload*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditImageUploadCall.html), [*insert*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditInsertCall.html), [*listings delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditListingDeleteCall.html), [*listings deleteall*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditListingDeleteallCall.html), [*listings get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditListingGetCall.html), [*listings list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditListingListCall.html), [*listings patch*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditListingPatchCall.html), [*listings update*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditListingUpdateCall.html), [*testers get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditTesterGetCall.html), [*testers patch*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditTesterPatchCall.html), [*testers update*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditTesterUpdateCall.html), [*tracks create*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditTrackCreateCall.html), [*tracks get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditTrackGetCall.html), [*tracks list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditTrackListCall.html), [*tracks patch*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditTrackPatchCall.html), [*tracks update*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditTrackUpdateCall.html) and [*validate*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditValidateCall.html)
* externaltransactions
 * [*createexternaltransaction*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ExternaltransactionCreateexternaltransactionCall.html), [*getexternaltransaction*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ExternaltransactionGetexternaltransactionCall.html) and [*refundexternaltransaction*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ExternaltransactionRefundexternaltransactionCall.html)
* generatedapks
 * [*download*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.GeneratedapkDownloadCall.html) and [*list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.GeneratedapkListCall.html)
* [grants](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.Grant.html)
 * [*create*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.GrantCreateCall.html), [*delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.GrantDeleteCall.html) and [*patch*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.GrantPatchCall.html)
* inappproducts
 * [*batch delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InappproductBatchDeleteCall.html), [*batch get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InappproductBatchGetCall.html), [*batch update*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InappproductBatchUpdateCall.html), [*delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InappproductDeleteCall.html), [*get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InappproductGetCall.html), [*insert*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InappproductInsertCall.html), [*list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InappproductListCall.html), [*patch*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InappproductPatchCall.html) and [*update*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InappproductUpdateCall.html)
* internalappsharingartifacts
 * [*uploadapk*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InternalappsharingartifactUploadapkCall.html) and [*uploadbundle*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InternalappsharingartifactUploadbundleCall.html)
* monetization
 * [*convert region prices*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationConvertRegionPriceCall.html), [*onetimeproducts batch delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductBatchDeleteCall.html), [*onetimeproducts batch get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductBatchGetCall.html), [*onetimeproducts batch update*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductBatchUpdateCall.html), [*onetimeproducts delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductDeleteCall.html), [*onetimeproducts get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductGetCall.html), [*onetimeproducts list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductListCall.html), [*onetimeproducts patch*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductPatchCall.html), [*onetimeproducts purchase options batch delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductPurchaseOptionBatchDeleteCall.html), [*onetimeproducts purchase options batch update states*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductPurchaseOptionBatchUpdateStateCall.html), [*onetimeproducts purchase options offers activate*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductPurchaseOptionOfferActivateCall.html), [*onetimeproducts purchase options offers batch delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductPurchaseOptionOfferBatchDeleteCall.html), [*onetimeproducts purchase options offers batch get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductPurchaseOptionOfferBatchGetCall.html), [*onetimeproducts purchase options offers batch update*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductPurchaseOptionOfferBatchUpdateCall.html), [*onetimeproducts purchase options offers batch update states*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductPurchaseOptionOfferBatchUpdateStateCall.html), [*onetimeproducts purchase options offers cancel*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductPurchaseOptionOfferCancelCall.html), [*onetimeproducts purchase options offers deactivate*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductPurchaseOptionOfferDeactivateCall.html), [*onetimeproducts purchase options offers list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationOnetimeproductPurchaseOptionOfferListCall.html), [*subscriptions archive*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionArchiveCall.html), [*subscriptions base plans activate*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanActivateCall.html), [*subscriptions base plans batch migrate prices*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanBatchMigratePriceCall.html), [*subscriptions base plans batch update states*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanBatchUpdateStateCall.html), [*subscriptions base plans deactivate*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanDeactivateCall.html), [*subscriptions base plans delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanDeleteCall.html), [*subscriptions base plans migrate prices*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanMigratePriceCall.html), [*subscriptions base plans offers activate*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanOfferActivateCall.html), [*subscriptions base plans offers batch get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanOfferBatchGetCall.html), [*subscriptions base plans offers batch update*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanOfferBatchUpdateCall.html), [*subscriptions base plans offers batch update states*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanOfferBatchUpdateStateCall.html), [*subscriptions base plans offers create*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanOfferCreateCall.html), [*subscriptions base plans offers deactivate*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanOfferDeactivateCall.html), [*subscriptions base plans offers delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanOfferDeleteCall.html), [*subscriptions base plans offers get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanOfferGetCall.html), [*subscriptions base plans offers list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanOfferListCall.html), [*subscriptions base plans offers patch*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBasePlanOfferPatchCall.html), [*subscriptions batch get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBatchGetCall.html), [*subscriptions batch update*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionBatchUpdateCall.html), [*subscriptions create*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionCreateCall.html), [*subscriptions delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionDeleteCall.html), [*subscriptions get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionGetCall.html), [*subscriptions list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionListCall.html) and [*subscriptions patch*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.MonetizationSubscriptionPatchCall.html)
* [orders](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.Order.html)
 * [*batchget*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.OrderBatchgetCall.html), [*get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.OrderGetCall.html) and [*refund*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.OrderRefundCall.html)
* purchases
 * [*products acknowledge*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseProductAcknowledgeCall.html), [*products consume*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseProductConsumeCall.html), [*products get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseProductGetCall.html), [*productsv2 getproductpurchasev2*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseProductsv2Getproductpurchasev2Call.html), [*subscriptions acknowledge*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseSubscriptionAcknowledgeCall.html), [*subscriptions cancel*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseSubscriptionCancelCall.html), [*subscriptions defer*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseSubscriptionDeferCall.html), [*subscriptions get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseSubscriptionGetCall.html), [*subscriptions refund*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseSubscriptionRefundCall.html), [*subscriptions revoke*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseSubscriptionRevokeCall.html), [*subscriptionsv2 cancel*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseSubscriptionsv2CancelCall.html), [*subscriptionsv2 get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseSubscriptionsv2GetCall.html), [*subscriptionsv2 revoke*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseSubscriptionsv2RevokeCall.html) and [*voidedpurchases list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.PurchaseVoidedpurchaseListCall.html)
* [reviews](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.Review.html)
 * [*get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ReviewGetCall.html), [*list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ReviewListCall.html) and [*reply*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.ReviewReplyCall.html)
* systemapks
 * [*variants create*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.SystemapkVariantCreateCall.html), [*variants download*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.SystemapkVariantDownloadCall.html), [*variants get*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.SystemapkVariantGetCall.html) and [*variants list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.SystemapkVariantListCall.html)
* [users](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.User.html)
 * [*create*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.UserCreateCall.html), [*delete*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.UserDeleteCall.html), [*list*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.UserListCall.html) and [*patch*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.UserPatchCall.html)


Upload supported by ...

* [*apks upload edits*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditApkUploadCall.html)
* [*bundles upload edits*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditBundleUploadCall.html)
* [*deobfuscationfiles upload edits*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditDeobfuscationfileUploadCall.html)
* [*expansionfiles upload edits*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditExpansionfileUploadCall.html)
* [*images upload edits*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.EditImageUploadCall.html)
* [*uploadapk internalappsharingartifacts*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InternalappsharingartifactUploadapkCall.html)
* [*uploadbundle internalappsharingartifacts*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.InternalappsharingartifactUploadbundleCall.html)

Download supported by ...

* [*download generatedapks*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.GeneratedapkDownloadCall.html)
* [*variants download systemapks*](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.SystemapkVariantDownloadCall.html)



# Structure of this Library

The API is structured into the following primary items:

* **[Hub](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/api/struct.AndroidPublisher.html)**
    * a central object to maintain state and allow accessing all *Activities*
    * creates [*Method Builders*](https://docs.rs/google-apis-common/latest/google_apis_common/trait.MethodsBuilder.html) which in turn
      allow access to individual [*Call Builders*](https://docs.rs/google-apis-common/latest/google_apis_common/trait.CallBuilder.html)
* **[Resources](https://docs.rs/google-apis-common/latest/google_apis_common/trait.Resource.html)**
    * primary types that you can apply *Activities* to
    * a collection of properties and *Parts*
    * **[Parts](https://docs.rs/google-apis-common/latest/google_apis_common/trait.Part.html)**
        * a collection of properties
        * never directly used in *Activities*
* **[Activities](https://docs.rs/google-apis-common/latest/google_apis_common/trait.CallBuilder.html)**
    * operations to apply to *Resources*

All *structures* are marked with applicable traits to further categorize them and ease browsing.

Generally speaking, you can invoke *Activities* like this:

```Rust,ignore
let r = hub.resource().activity(...).doit().await
```

Or specifically ...

```ignore
let r = hub.monetization().subscriptions_base_plans_activate(...).doit().await
let r = hub.monetization().subscriptions_base_plans_deactivate(...).doit().await
let r = hub.monetization().subscriptions_archive(...).doit().await
let r = hub.monetization().subscriptions_create(...).doit().await
let r = hub.monetization().subscriptions_get(...).doit().await
let r = hub.monetization().subscriptions_patch(...).doit().await
```

The `resource()` and `activity(...)` calls create [builders][builder-pattern]. The second one dealing with `Activities`
supports various methods to configure the impending operation (not shown here). It is made such that all required arguments have to be
specified right away (i.e. `(...)`), whereas all optional ones can be [build up][builder-pattern] as desired.
The `doit()` method performs the actual communication with the server and returns the respective result.

# Usage

## Setting up your Project

To use this library, you would put the following lines into your `Cargo.toml` file:

```toml
[dependencies]
google-androidpublisher3 = "*"
serde = "1"
serde_json = "1"
```

## A complete example

```Rust
extern crate hyper;
extern crate hyper_rustls;
extern crate google_androidpublisher3 as androidpublisher3;
use androidpublisher3::api::Subscription;
use androidpublisher3::{Result, Error};
use androidpublisher3::{AndroidPublisher, FieldMask, hyper_rustls, hyper_util, yup_oauth2};

// Get an ApplicationSecret instance by some means. It contains the `client_id` and
// `client_secret`, among other things.
let secret: yup_oauth2::ApplicationSecret = Default::default();
// Instantiate the authenticator. It will choose a suitable authentication flow for you,
// unless you replace  `None` with the desired Flow.
// Provide your own `AuthenticatorDelegate` to adjust the way it operates and get feedback about
// what's going on. You probably want to bring in your own `TokenStorage` to persist tokens and
// retrieve them from storage.
let connector = hyper_rustls::HttpsConnectorBuilder::new()
    .with_native_roots()
    .unwrap()
    .https_only()
    .enable_http2()
    .build();

let executor = hyper_util::rt::TokioExecutor::new();
let auth = yup_oauth2::InstalledFlowAuthenticator::with_client(
    secret,
    yup_oauth2::InstalledFlowReturnMethod::HTTPRedirect,
    yup_oauth2::client::CustomHyperClientBuilder::from(
        hyper_util::client::legacy::Client::builder(executor).build(connector),
    ),
).build().await.unwrap();

let client = hyper_util::client::legacy::Client::builder(
    hyper_util::rt::TokioExecutor::new()
)
.build(
    hyper_rustls::HttpsConnectorBuilder::new()
        .with_native_roots()
        .unwrap()
        .https_or_http()
        .enable_http2()
        .build()
);
let mut hub = AndroidPublisher::new(client, auth);
// As the method needs a request, you would usually fill it with the desired information
// into the respective structure. Some of the parts shown here might not be applicable !
// Values shown here are possibly random and not representative !
let mut req = Subscription::default();

// You can configure optional parameters by calling the respective setters at will, and
// execute the final call using `doit()`.
// Values shown here are possibly random and not representative !
let result = hub.monetization().subscriptions_patch(req, "packageName", "productId")
             .update_mask(FieldMask::new::<&str>(&[]))
             .regions_version_version("no")
             .latency_tolerance("ipsum")
             .allow_missing(false)
             .doit().await;

match result {
    Err(e) => match e {
        // The Error enum provides details about what exactly happened.
        // You can also just use its `Debug`, `Display` or `Error` traits
         Error::HttpError(_)
        |Error::Io(_)
        |Error::MissingAPIKey
        |Error::MissingToken(_)
        |Error::Cancelled
        |Error::UploadSizeLimitExceeded(_, _)
        |Error::Failure(_)
        |Error::BadRequest(_)
        |Error::FieldClash(_)
        |Error::JsonDecodeError(_, _) => println!("{}", e),
    },
    Ok(res) => println!("Success: {:?}", res),
}

```
## Handling Errors

All errors produced by the system are provided either as [Result](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/type.Result.html) enumeration as return value of
the doit() methods, or handed as possibly intermediate results to either the
[Hub Delegate](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/trait.Delegate.html), or the [Authenticator Delegate](https://docs.rs/yup-oauth2/*/yup_oauth2/trait.AuthenticatorDelegate.html).

When delegates handle errors or intermediate values, they may have a chance to instruct the system to retry. This
makes the system potentially resilient to all kinds of errors.

## Uploads and Downloads
If a method supports downloads, the response body, which is part of the [Result](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/type.Result.html), should be
read by you to obtain the media.
If such a method also supports a [Response Result](https://docs.rs/google-apis-common/latest/google_apis_common/trait.ResponseResult.html), it will return that by default.
You can see it as meta-data for the actual media. To trigger a media download, you will have to set up the builder by making
this call: `.param("alt", "media")`.

Methods supporting uploads can do so using up to 2 different protocols:
*simple* and *resumable*. The distinctiveness of each is represented by customized
`doit(...)` methods, which are then named `upload(...)` and `upload_resumable(...)` respectively.

## Customization and Callbacks

You may alter the way an `doit()` method is called by providing a [delegate](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/trait.Delegate.html) to the
[Method Builder](https://docs.rs/google-apis-common/latest/google_apis_common/trait.CallBuilder.html) before making the final `doit()` call.
Respective methods will be called to provide progress information, as well as determine whether the system should
retry on failure.

The [delegate trait](https://docs.rs/google-androidpublisher3/7.0.0+20251216/google_androidpublisher3/trait.Delegate.html) is default-implemented, allowing you to customize it with minimal effort.

## Optional Parts in Server-Requests

All structures provided by this library are made to be [encodable](https://docs.rs/google-apis-common/latest/google_apis_common/trait.RequestValue.html) and
[decodable](https://docs.rs/google-apis-common/latest/google_apis_common/trait.ResponseResult.html) via *json*. Optionals are used to indicate that partial requests are responses
are valid.
Most optionals are are considered [Parts](https://docs.rs/google-apis-common/latest/google_apis_common/trait.Part.html) which are identifiable by name, which will be sent to
the server to indicate either the set parts of the request or the desired parts in the response.

## Builder Arguments

Using [method builders](https://docs.rs/google-apis-common/latest/google_apis_common/trait.CallBuilder.html), you are able to prepare an action call by repeatedly calling it's methods.
These will always take a single argument, for which the following statements are true.

* [PODs][wiki-pod] are handed by copy
* strings are passed as `&str`
* [request values](https://docs.rs/google-apis-common/latest/google_apis_common/trait.RequestValue.html) are moved

Arguments will always be copied or cloned into the builder, to make them independent of their original life times.

[wiki-pod]: http://en.wikipedia.org/wiki/Plain_old_data_structure
[builder-pattern]: http://en.wikipedia.org/wiki/Builder_pattern
[google-go-api]: https://github.com/google/google-api-go-client

## Cargo Features

* `utoipa` - Add support for [utoipa](https://crates.io/crates/utoipa) and derive `utoipa::ToSchema` on all
the types. You'll have to import and register the required types in `#[openapi(schemas(...))]`, otherwise the
generated `openapi` spec would be invalid.


# License
The **androidpublisher3** library was generated by Sebastian Thiel, and is placed
under the *MIT* license.
You can read the full text at the repository's [license file][repo-license].

[repo-license]: https://github.com/Byron/google-apis-rsblob/main/LICENSE.md

