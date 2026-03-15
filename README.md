# Server Metrics 2026-03-15 13:49:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 56103.3 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1696271
telemt_connections_bad_total 97055
telemt_handshake_timeouts_total 17058
telemt_upstream_connect_attempt_total 11198
telemt_upstream_connect_success_total 11149
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13207
telemt_me_reconnect_success_total 8319
telemt_me_reader_eof_total 8917
telemt_me_idle_close_by_peer_total 8917
telemt_me_route_drop_no_conn_total 577196
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1430026
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5323
telemt_desync_full_logged_total 1480
telemt_desync_suppressed_total 3843
telemt_desync_frames_bucket_total{bucket="1_2"} 1373
telemt_desync_frames_bucket_total{bucket="3_10"} 2066
telemt_desync_frames_bucket_total{bucket="gt_10"} 1884
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8603
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8308
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 1429663
telemt_user_connections_current{user="hello"} 2246
telemt_user_octets_from_client{user="hello"} 20561116228 (19.15 GB)
telemt_user_octets_to_client{user="hello"} 567617383888 (528.63 GB)
telemt_user_unique_ips_current{user="hello"} 649
telemt_user_unique_ips_recent_window{user="hello"} 293
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 56104.2 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 685353
telemt_connections_bad_total 36471
telemt_handshake_timeouts_total 52139
telemt_upstream_connect_attempt_total 14427
telemt_upstream_connect_success_total 14357
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 14427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11278
telemt_me_reconnect_success_total 11192
telemt_me_reader_eof_total 11830
telemt_me_idle_close_by_peer_total 11830
telemt_me_route_drop_no_conn_total 170483
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 515500
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1970
telemt_desync_full_logged_total 679
telemt_desync_suppressed_total 1291
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 520
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11329
telemt_me_writer_restored_same_endpoint_total 11180
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 515766
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 7291948571 (6.79 GB)
telemt_user_octets_to_client{user="hello"} 195948169512 (182.49 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 56104.1 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1440107
telemt_connections_bad_total 43662
telemt_handshake_timeouts_total 150229
telemt_upstream_connect_attempt_total 12428
telemt_upstream_connect_success_total 12371
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 12428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 10778
telemt_me_reconnect_success_total 9526
telemt_me_reader_eof_total 10102
telemt_me_idle_close_by_peer_total 10102
telemt_me_route_drop_no_conn_total 397942
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 912478
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2323
telemt_desync_full_logged_total 850
telemt_desync_suppressed_total 1473
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 890
telemt_desync_frames_bucket_total{bucket="gt_10"} 910
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9689
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9507
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 908958
telemt_user_connections_current{user="hello"} 1252
telemt_user_octets_from_client{user="hello"} 13099384452 (12.20 GB)
telemt_user_octets_to_client{user="hello"} 330775587232 (308.06 GB)
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 56104.0 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 698034
telemt_connections_bad_total 70218
telemt_handshake_timeouts_total 37569
telemt_upstream_connect_attempt_total 96332
telemt_upstream_connect_success_total 95884
telemt_upstream_connect_fail_total 447
telemt_upstream_connect_attempts_per_request{bucket="1"} 96331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 447
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 48120
telemt_me_reconnect_success_total 11784
telemt_me_reader_eof_total 13251
telemt_me_idle_close_by_peer_total 13251
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 169267
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443301
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1167
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 872
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 13030
telemt_me_refill_failed_total 1136
telemt_me_writer_restored_same_endpoint_total 11752
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1246
telemt_user_connections_total{user="hello"} 524450
telemt_user_connections_current{user="hello"} 806
telemt_user_octets_from_client{user="hello"} 9669066690 (9.01 GB)
telemt_user_octets_to_client{user="hello"} 180075211108 (167.71 GB)
telemt_user_msgs_from_client{user="hello"} 1512186
telemt_user_msgs_to_client{user="hello"} 5752279
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 56105.1 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 724335
telemt_connections_bad_total 9140
telemt_handshake_timeouts_total 15165
telemt_upstream_connect_attempt_total 12377
telemt_upstream_connect_success_total 12309
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 12377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 13156
telemt_me_reconnect_success_total 9484
telemt_me_reader_eof_total 10158
telemt_me_idle_close_by_peer_total 10158
telemt_me_route_drop_no_conn_total 180452
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 589405
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2188
telemt_desync_full_logged_total 736
telemt_desync_suppressed_total 1452
telemt_desync_frames_bucket_total{bucket="1_2"} 652
telemt_desync_frames_bucket_total{bucket="3_10"} 860
telemt_desync_frames_bucket_total{bucket="gt_10"} 676
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9712
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9476
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 589445
telemt_user_connections_current{user="hello"} 918
telemt_user_octets_from_client{user="hello"} 7410758628 (6.90 GB)
telemt_user_octets_to_client{user="hello"} 221888716068 (206.65 GB)
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 109
```