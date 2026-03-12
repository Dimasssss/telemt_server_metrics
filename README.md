# Server Metrics 2026-03-12 16:32:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 38016.1 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1373834
telemt_connections_bad_total 20244
telemt_handshake_timeouts_total 13160
telemt_upstream_connect_attempt_total 7677
telemt_upstream_connect_success_total 7634
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 459
telemt_me_reconnect_attempts_total 10652
telemt_me_reconnect_success_total 5683
telemt_me_reader_eof_total 6073
telemt_me_idle_close_by_peer_total 6072
telemt_me_route_drop_no_conn_total 495158
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1287742
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6632
telemt_desync_full_logged_total 1660
telemt_desync_suppressed_total 4972
telemt_desync_frames_bucket_total{bucket="1_2"} 1711
telemt_desync_frames_bucket_total{bucket="3_10"} 2399
telemt_desync_frames_bucket_total{bucket="gt_10"} 2522
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5913
telemt_me_refill_failed_total 154
telemt_me_writer_restored_same_endpoint_total 5670
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 1287417
telemt_user_connections_current{user="hello"} 1647
telemt_user_octets_from_client{user="hello"} 19706565476 (18.35 GB)
telemt_user_octets_to_client{user="hello"} 371211010964 (345.72 GB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 67636.8 (18h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 604497
telemt_connections_bad_total 7936
telemt_handshake_timeouts_total 28373
telemt_upstream_connect_attempt_total 16116
telemt_upstream_connect_success_total 16109
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1259
telemt_me_reconnect_attempts_total 12600
telemt_me_reconnect_success_total 12528
telemt_me_reader_eof_total 13317
telemt_me_idle_close_by_peer_total 13317
telemt_me_route_drop_no_conn_total 182214
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541328
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2150
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1469
telemt_desync_frames_bucket_total{bucket="1_2"} 952
telemt_desync_frames_bucket_total{bucket="3_10"} 685
telemt_desync_frames_bucket_total{bucket="gt_10"} 513
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12654
telemt_me_writer_restored_same_endpoint_total 12519
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 541832
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 8342589083 (7.77 GB)
telemt_user_octets_to_client{user="hello"} 190363418418 (177.29 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 67636.4 (18h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1274282
telemt_connections_bad_total 6406
telemt_handshake_timeouts_total 91256
telemt_upstream_connect_attempt_total 16199
telemt_upstream_connect_success_total 16194
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1069
telemt_me_reconnect_attempts_total 13663
telemt_me_reconnect_success_total 12432
telemt_me_reader_eof_total 13112
telemt_me_idle_close_by_peer_total 13111
telemt_me_route_drop_no_conn_total 351684
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 949520
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4033
telemt_desync_full_logged_total 1238
telemt_desync_suppressed_total 2795
telemt_desync_frames_bucket_total{bucket="1_2"} 624
telemt_desync_frames_bucket_total{bucket="3_10"} 1458
telemt_desync_frames_bucket_total{bucket="gt_10"} 1951
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12524
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12391
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 949678
telemt_user_connections_current{user="hello"} 1039
telemt_user_octets_from_client{user="hello"} 12331991884 (11.49 GB)
telemt_user_octets_to_client{user="hello"} 297373789217 (276.95 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 67637.1 (18h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 763206
telemt_connections_bad_total 7728
telemt_handshake_timeouts_total 60486
telemt_upstream_connect_attempt_total 17744
telemt_upstream_connect_success_total 17672
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 17743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1504
telemt_me_reconnect_attempts_total 19515
telemt_me_reconnect_success_total 14268
telemt_me_reader_eof_total 15207
telemt_me_idle_close_by_peer_total 15207
telemt_me_route_drop_no_conn_total 261248
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 659409
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1340
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 892
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 526
telemt_desync_frames_bucket_total{bucket="gt_10"} 443
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 14541
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14247
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 273
telemt_user_connections_total{user="hello"} 658848
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 8160015680 (7.60 GB)
telemt_user_octets_to_client{user="hello"} 255235377004 (237.71 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 67637.2 (18h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 861932
telemt_connections_bad_total 10745
telemt_handshake_timeouts_total 7099
telemt_upstream_connect_attempt_total 21270
telemt_upstream_connect_success_total 21009
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 21270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10189
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 1216
telemt_me_reconnect_attempts_total 24843
telemt_me_reconnect_success_total 17600
telemt_me_reader_eof_total 18419
telemt_me_idle_close_by_peer_total 18419
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 304590
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 792039
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3118
telemt_desync_full_logged_total 1056
telemt_desync_suppressed_total 2062
telemt_desync_frames_bucket_total{bucket="1_2"} 857
telemt_desync_frames_bucket_total{bucket="3_10"} 1066
telemt_desync_frames_bucket_total{bucket="gt_10"} 1195
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 18012
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 17560
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 412
telemt_user_connections_total{user="hello"} 791932
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 9773378796 (9.10 GB)
telemt_user_octets_to_client{user="hello"} 223665009964 (208.30 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 133
```