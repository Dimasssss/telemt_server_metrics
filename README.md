# Server Metrics 2026-02-26 03:50:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 17579.9 (4h 52m)
telemt_connections_total 137999
telemt_connections_bad_total 1012
telemt_handshake_timeouts_total 10729
telemt_me_keepalive_sent_total 19057
telemt_me_keepalive_pong_total 19055
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 591
telemt_me_reconnect_success_total 650
telemt_me_route_drop_no_conn_total 21152
telemt_desync_total 60
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 18
telemt_pool_force_close_total 228
telemt_pool_stale_pick_total 4410
telemt_me_writer_removed_total 1114
telemt_me_writer_removed_unexpected_total 616
telemt_me_refill_triggered_total 584
telemt_me_refill_skipped_inflight_total 32
telemt_me_writer_restored_same_endpoint_total 581
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 120390
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 800097096 (763.03 MB)
telemt_user_octets_to_client{user="hello"} 23574614768 (21.96 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 18374.2 (5h 6m)
telemt_connections_total 70769
telemt_connections_bad_total 1457
telemt_handshake_timeouts_total 7539
telemt_me_keepalive_sent_total 20751
telemt_me_keepalive_pong_total 20745
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 1292
telemt_me_reconnect_success_total 1376
telemt_me_route_drop_no_conn_total 10850
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 41
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 19
telemt_pool_drain_active 12
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 2747
telemt_me_writer_removed_total 1834
telemt_me_writer_removed_unexpected_total 1318
telemt_me_refill_triggered_total 1278
telemt_me_refill_skipped_inflight_total 40
telemt_me_writer_restored_same_endpoint_total 1272
telemt_me_writer_restored_fallback_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 55888
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 215414236 (205.44 MB)
telemt_user_octets_to_client{user="hello"} 12218829032 (11.38 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 26101.9 (7h 15m)
telemt_connections_total 106846
telemt_connections_bad_total 1371
telemt_handshake_timeouts_total 19847
telemt_me_keepalive_sent_total 28487
telemt_me_keepalive_pong_total 28475
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 2452
telemt_me_reconnect_success_total 2588
telemt_me_route_drop_no_conn_total 20083
telemt_desync_total 228
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 27
telemt_pool_force_close_total 264
telemt_pool_stale_pick_total 2932
telemt_me_writer_removed_total 3278
telemt_me_writer_removed_unexpected_total 2509
telemt_me_refill_triggered_total 2436
telemt_me_refill_skipped_inflight_total 73
telemt_me_writer_restored_same_endpoint_total 2431
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 82921
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 637876784 (608.33 MB)
telemt_user_octets_to_client{user="hello"} 22020323596 (20.51 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 28507.5 (7h 55m)
telemt_connections_total 150248
telemt_connections_bad_total 3964
telemt_handshake_timeouts_total 9936
telemt_me_keepalive_sent_total 31667
telemt_me_keepalive_pong_total 31648
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 1502
telemt_me_reconnect_success_total 1627
telemt_me_route_drop_no_conn_total 35951
telemt_me_route_drop_channel_closed_total 2
telemt_desync_total 252
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 29
telemt_pool_force_close_total 310
telemt_pool_stale_pick_total 5663
telemt_me_writer_removed_total 2359
telemt_me_writer_removed_unexpected_total 1563
telemt_me_refill_triggered_total 1475
telemt_me_refill_skipped_inflight_total 88
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1468
telemt_me_writer_restored_fallback_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 123723
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 471306268 (449.47 MB)
telemt_user_octets_to_client{user="hello"} 17273773648 (16.09 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 28820.1 (8h 0m)
telemt_connections_total 177464
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 16395
telemt_me_keepalive_sent_total 31906
telemt_me_keepalive_pong_total 31880
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 1327
telemt_me_reconnect_success_total 1444
telemt_me_route_drop_no_conn_total 51290
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 267
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 30
telemt_pool_force_close_total 441
telemt_pool_stale_pick_total 6437
telemt_me_writer_removed_total 2223
telemt_me_writer_removed_unexpected_total 1390
telemt_me_refill_triggered_total 1305
telemt_me_refill_skipped_inflight_total 85
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 1293
telemt_me_writer_restored_fallback_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 157941
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 3204190528 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 51837384312 (48.28 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 26063.6 (7h 14m)
telemt_connections_total 278
telemt_connections_bad_total 90
telemt_handshake_timeouts_total 1
telemt_me_keepalive_sent_total 28150
telemt_me_keepalive_pong_total 28116
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8123
telemt_me_reconnect_success_total 8409
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 8
telemt_pool_swap_total 27
telemt_pool_force_close_total 90
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_total 9015
telemt_me_writer_removed_unexpected_total 8332
telemt_me_refill_triggered_total 8118
telemt_me_refill_skipped_inflight_total 214
telemt_me_writer_restored_same_endpoint_total 8116
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello1"} 183
telemt_user_connections_current{user="hello1"} 4
telemt_user_octets_from_client{user="hello1"} 601496 (587.40 KB)
telemt_user_octets_to_client{user="hello1"} 12168756 (11.61 MB)
```