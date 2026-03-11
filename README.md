# Server Metrics 2026-03-11 09:45:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 69485.3 (19h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1491252
telemt_connections_bad_total 19589
telemt_handshake_timeouts_total 40769
telemt_upstream_connect_attempt_total 14430
telemt_upstream_connect_success_total 14421
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 780
telemt_me_reconnect_attempts_total 22585
telemt_me_reconnect_success_total 10896
telemt_me_reader_eof_total 11808
telemt_me_idle_close_by_peer_total 11808
telemt_me_route_drop_no_conn_total 550961
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1355314
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6702
telemt_desync_full_logged_total 1851
telemt_desync_suppressed_total 4851
telemt_desync_frames_bucket_total{bucket="1_2"} 1764
telemt_desync_frames_bucket_total{bucket="3_10"} 2550
telemt_desync_frames_bucket_total{bucket="gt_10"} 2388
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 11368
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10890
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 472
telemt_user_connections_total{user="hello"} 1353926
telemt_user_connections_current{user="hello"} 1361
telemt_user_octets_from_client{user="hello"} 17842730024 (16.62 GB)
telemt_user_octets_to_client{user="hello"} 388658910820 (361.97 GB)
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 69542.1 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 572539
telemt_connections_bad_total 10169
telemt_handshake_timeouts_total 31668
telemt_upstream_connect_attempt_total 23438
telemt_upstream_connect_success_total 20509
telemt_upstream_connect_fail_total 2929
telemt_upstream_connect_attempts_per_request{bucket="1"} 23438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2929
telemt_me_keepalive_timeout_total 2108
telemt_me_reconnect_attempts_total 14906
telemt_me_reconnect_success_total 14068
telemt_me_reader_eof_total 14900
telemt_me_idle_close_by_peer_total 14898
telemt_me_route_drop_no_conn_total 237820
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 485659
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2233
telemt_desync_full_logged_total 686
telemt_desync_suppressed_total 1547
telemt_desync_frames_bucket_total{bucket="1_2"} 747
telemt_desync_frames_bucket_total{bucket="3_10"} 798
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 14233
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14046
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 487900
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 4740549390 (4.41 GB)
telemt_user_octets_to_client{user="hello"} 134761550196 (125.51 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 69542.0 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 998054
telemt_connections_bad_total 7602
telemt_handshake_timeouts_total 98094
telemt_upstream_connect_attempt_total 18784
telemt_upstream_connect_success_total 18553
telemt_upstream_connect_fail_total 231
telemt_upstream_connect_attempts_per_request{bucket="1"} 18784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 231
telemt_me_keepalive_timeout_total 769
telemt_me_reconnect_attempts_total 26346
telemt_me_reconnect_success_total 13979
telemt_me_reader_eof_total 15017
telemt_me_idle_close_by_peer_total 15017
telemt_me_route_drop_no_conn_total 328002
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 853234
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2449
telemt_desync_full_logged_total 724
telemt_desync_suppressed_total 1725
telemt_desync_frames_bucket_total{bucket="1_2"} 587
telemt_desync_frames_bucket_total{bucket="3_10"} 895
telemt_desync_frames_bucket_total{bucket="gt_10"} 967
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 14549
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13968
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 854111
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 10099700093 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 260881305989 (242.96 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 69542.4 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727563
telemt_connections_bad_total 65402
telemt_handshake_timeouts_total 70147
telemt_upstream_connect_attempt_total 19083
telemt_upstream_connect_success_total 19083
telemt_upstream_connect_attempts_per_request{bucket="1"} 19083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 712
telemt_me_reconnect_attempts_total 16652
telemt_me_reconnect_success_total 15598
telemt_me_reader_eof_total 16570
telemt_me_idle_close_by_peer_total 16569
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 227464
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 569920
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1263
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 786
telemt_desync_frames_bucket_total{bucket="1_2"} 431
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 15784
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15575
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 569295
telemt_user_connections_current{user="hello"} 581
telemt_user_octets_from_client{user="hello"} 6635677160 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 162281112832 (151.14 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 69542.0 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 772948
telemt_connections_bad_total 5998
telemt_handshake_timeouts_total 7387
telemt_upstream_connect_attempt_total 18852
telemt_upstream_connect_success_total 18775
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 18852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 769
telemt_me_reconnect_attempts_total 18965
telemt_me_reconnect_success_total 15172
telemt_me_reader_eof_total 16045
telemt_me_idle_close_by_peer_total 16045
telemt_me_route_drop_no_conn_total 265062
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 700626
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2966
telemt_desync_full_logged_total 1122
telemt_desync_suppressed_total 1844
telemt_desync_frames_bucket_total{bucket="1_2"} 1037
telemt_desync_frames_bucket_total{bucket="3_10"} 1214
telemt_desync_frames_bucket_total{bucket="gt_10"} 715
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 15484
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15172
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 700309
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 11025498207 (10.27 GB)
telemt_user_octets_to_client{user="hello"} 254029423642 (236.58 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 88
```