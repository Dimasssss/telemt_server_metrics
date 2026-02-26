# Server Metrics 2026-02-26 16:17:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 62371.0 (17h 19m)
telemt_connections_total 1260894
telemt_connections_bad_total 7019
telemt_handshake_timeouts_total 191987
telemt_me_keepalive_sent_total 68265
telemt_me_keepalive_pong_total 68208
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1695
telemt_me_reconnect_success_total 1797
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 381363
telemt_me_route_drop_channel_closed_total 4
telemt_desync_total 2221
telemt_desync_full_logged_total 824
telemt_desync_suppressed_total 1397
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 799
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 65
telemt_pool_force_close_total 1011
telemt_pool_stale_pick_total 35740
telemt_me_writer_removed_total 3520
telemt_me_writer_removed_unexpected_total 1715
telemt_me_refill_triggered_total 1617
telemt_me_refill_skipped_inflight_total 98
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 1594
telemt_me_writer_restored_fallback_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 1003598
telemt_user_connections_current{user="hello"} 600
telemt_user_octets_from_client{user="hello"} 8906854032 (8.30 GB)
telemt_user_octets_to_client{user="hello"} 269028121952 (250.55 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 30664.6 (8h 31m)
telemt_connections_total 275402
telemt_connections_bad_total 4772
telemt_handshake_timeouts_total 44790
telemt_me_keepalive_sent_total 34074
telemt_me_keepalive_pong_total 34045
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1385
telemt_me_reconnect_success_total 1456
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 81596
telemt_desync_total 687
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 486
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 31
telemt_pool_force_close_total 438
telemt_pool_stale_pick_total 9376
telemt_me_writer_removed_total 2247
telemt_me_writer_removed_unexpected_total 1423
telemt_me_refill_triggered_total 1348
telemt_me_refill_skipped_inflight_total 75
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1338
telemt_me_writer_restored_fallback_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 213089
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 4330377608 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 65527724348 (61.03 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 70892.8 (19h 41m)
telemt_connections_total 729257
telemt_connections_bad_total 1610
telemt_handshake_timeouts_total 177820
telemt_me_keepalive_sent_total 77096
telemt_me_keepalive_pong_total 77040
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 4119
telemt_me_reconnect_success_total 4367
telemt_me_route_drop_no_conn_total 145328
telemt_me_route_drop_channel_closed_total 4
telemt_desync_total 1344
telemt_desync_full_logged_total 408
telemt_desync_suppressed_total 936
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 412
telemt_desync_frames_bucket_total{bucket="gt_10"} 523
telemt_pool_swap_total 74
telemt_pool_force_close_total 855
telemt_pool_stale_pick_total 18972
telemt_me_writer_removed_total 6308
telemt_me_writer_removed_unexpected_total 4229
telemt_me_refill_triggered_total 4059
telemt_me_refill_skipped_inflight_total 170
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 4037
telemt_me_writer_restored_fallback_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 521857
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 4662579676 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 130771239128 (121.79 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 73298.4 (20h 21m)
telemt_connections_total 635871
telemt_connections_bad_total 8375
telemt_handshake_timeouts_total 126590
telemt_me_keepalive_sent_total 80776
telemt_me_keepalive_pong_total 80696
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 3082
telemt_me_reconnect_success_total 3282
telemt_me_route_drop_no_conn_total 154379
telemt_me_route_drop_channel_closed_total 6
telemt_desync_total 1025
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 686
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 403
telemt_desync_frames_bucket_total{bucket="gt_10"} 367
telemt_pool_swap_total 76
telemt_pool_drain_active 15
telemt_pool_force_close_total 863
telemt_pool_stale_pick_total 20913
telemt_me_writer_removed_total 5230
telemt_me_writer_removed_unexpected_total 3182
telemt_me_refill_triggered_total 3000
telemt_me_refill_skipped_inflight_total 182
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 2975
telemt_me_writer_restored_fallback_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 441289
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 3099644456 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 90265534916 (84.07 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 73611.3 (20h 26m)
telemt_connections_total 1223614
telemt_connections_bad_total 3978
telemt_handshake_timeouts_total 417937
telemt_me_keepalive_sent_total 81301
telemt_me_keepalive_pong_total 81262
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 2671
telemt_me_reconnect_success_total 2865
telemt_me_route_drop_no_conn_total 299710
telemt_me_route_drop_channel_closed_total 11
telemt_desync_total 2955
telemt_desync_full_logged_total 882
telemt_desync_suppressed_total 2073
telemt_desync_frames_bucket_total{bucket="1_2"} 1389
telemt_desync_frames_bucket_total{bucket="3_10"} 823
telemt_desync_frames_bucket_total{bucket="gt_10"} 743
telemt_pool_swap_total 77
telemt_pool_force_close_total 1233
telemt_pool_stale_pick_total 31248
telemt_me_writer_removed_total 4906
telemt_me_writer_removed_unexpected_total 2786
telemt_me_refill_triggered_total 2626
telemt_me_refill_skipped_inflight_total 160
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 2602
telemt_me_writer_restored_fallback_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 769999
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 8914593764 (8.30 GB)
telemt_user_octets_to_client{user="hello"} 282284500840 (262.90 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 10687.4 (2h 58m)
telemt_connections_total 332
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 2
telemt_me_keepalive_sent_total 33
telemt_me_keepalive_failed_total 6
telemt_me_keepalive_pong_total 15
telemt_user_connections_total{user="hello1"} 261
telemt_user_connections_current{user="hello1"} 17
telemt_user_octets_from_client{user="hello1"} 1423612 (1.36 MB)
telemt_user_octets_to_client{user="hello1"} 60676000 (57.87 MB)
telemt_user_msgs_from_client{user="hello1"} 5446
telemt_user_msgs_to_client{user="hello1"} 24630
```