# Server Metrics 2026-03-12 15:41:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 34952.3 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1257600
telemt_connections_bad_total 20235
telemt_handshake_timeouts_total 12446
telemt_upstream_connect_attempt_total 6998
telemt_upstream_connect_success_total 6961
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 417
telemt_me_reconnect_attempts_total 9098
telemt_me_reconnect_success_total 5192
telemt_me_reader_eof_total 5534
telemt_me_idle_close_by_peer_total 5533
telemt_me_route_drop_no_conn_total 449185
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1183641
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6234
telemt_desync_full_logged_total 1558
telemt_desync_suppressed_total 4676
telemt_desync_frames_bucket_total{bucket="1_2"} 1603
telemt_desync_frames_bucket_total{bucket="3_10"} 2237
telemt_desync_frames_bucket_total{bucket="gt_10"} 2394
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5378
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5179
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 1183327
telemt_user_connections_current{user="hello"} 1636
telemt_user_octets_from_client{user="hello"} 18486463228 (17.22 GB)
telemt_user_octets_to_client{user="hello"} 344171883872 (320.54 GB)
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 64572.8 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565713
telemt_connections_bad_total 7113
telemt_handshake_timeouts_total 27434
telemt_upstream_connect_attempt_total 15507
telemt_upstream_connect_success_total 15500
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1179
telemt_me_reconnect_attempts_total 12167
telemt_me_reconnect_success_total 12099
telemt_me_reader_eof_total 12859
telemt_me_idle_close_by_peer_total 12859
telemt_me_route_drop_no_conn_total 166386
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505234
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1945
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1328
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 619
telemt_desync_frames_bucket_total{bucket="gt_10"} 464
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12218
telemt_me_writer_restored_same_endpoint_total 12090
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 505731
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 7854668143 (7.32 GB)
telemt_user_octets_to_client{user="hello"} 179436906054 (167.11 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 64572.7 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1201310
telemt_connections_bad_total 6250
telemt_handshake_timeouts_total 83469
telemt_upstream_connect_attempt_total 15546
telemt_upstream_connect_success_total 15541
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7077
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 991
telemt_me_reconnect_attempts_total 13186
telemt_me_reconnect_success_total 11962
telemt_me_reader_eof_total 12616
telemt_me_idle_close_by_peer_total 12616
telemt_me_route_drop_no_conn_total 324276
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 886528
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3725
telemt_desync_full_logged_total 1144
telemt_desync_suppressed_total 2581
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 1355
telemt_desync_frames_bucket_total{bucket="gt_10"} 1805
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12048
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11921
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 886711
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 11772481772 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 278061403661 (258.96 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 64573.4 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 712932
telemt_connections_bad_total 7707
telemt_handshake_timeouts_total 58038
telemt_upstream_connect_attempt_total 17006
telemt_upstream_connect_success_total 16937
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 17006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1368
telemt_me_reconnect_attempts_total 18955
telemt_me_reconnect_success_total 13714
telemt_me_reader_eof_total 14625
telemt_me_idle_close_by_peer_total 14625
telemt_me_route_drop_no_conn_total 242272
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 612987
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1236
telemt_desync_full_logged_total 422
telemt_desync_suppressed_total 814
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 413
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13981
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 13693
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 612474
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 7738900764 (7.21 GB)
telemt_user_octets_to_client{user="hello"} 241592065092 (225.00 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 64573.0 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 804491
telemt_connections_bad_total 8266
telemt_handshake_timeouts_total 6335
telemt_upstream_connect_attempt_total 20463
telemt_upstream_connect_success_total 20211
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 20463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9838
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 1122
telemt_me_reconnect_attempts_total 24224
telemt_me_reconnect_success_total 16986
telemt_me_reader_eof_total 17794
telemt_me_idle_close_by_peer_total 17794
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 281883
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 742459
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2922
telemt_desync_full_logged_total 989
telemt_desync_suppressed_total 1933
telemt_desync_frames_bucket_total{bucket="1_2"} 824
telemt_desync_frames_bucket_total{bucket="3_10"} 998
telemt_desync_frames_bucket_total{bucket="gt_10"} 1100
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 17389
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 16952
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 403
telemt_user_connections_total{user="hello"} 742356
telemt_user_connections_current{user="hello"} 858
telemt_user_octets_from_client{user="hello"} 8927744100 (8.31 GB)
telemt_user_octets_to_client{user="hello"} 208592840064 (194.27 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 109
```