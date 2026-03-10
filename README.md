# Server Metrics 2026-03-10 20:11:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 20672.8 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 622903
telemt_connections_bad_total 8007
telemt_handshake_timeouts_total 6192
telemt_upstream_connect_attempt_total 4252
telemt_upstream_connect_success_total 4243
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2115
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 333
telemt_me_reconnect_attempts_total 13618
telemt_me_reconnect_success_total 3153
telemt_me_reader_eof_total 3503
telemt_me_idle_close_by_peer_total 3503
telemt_me_route_drop_no_conn_total 260856
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 587905
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3088
telemt_desync_full_logged_total 834
telemt_desync_suppressed_total 2254
telemt_desync_frames_bucket_total{bucket="1_2"} 861
telemt_desync_frames_bucket_total{bucket="3_10"} 1169
telemt_desync_frames_bucket_total{bucket="gt_10"} 1058
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3499
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 3147
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 346
telemt_user_connections_total{user="hello"} 587727
telemt_user_connections_current{user="hello"} 1026
telemt_user_octets_from_client{user="hello"} 8435391244 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 174469316392 (162.49 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 20729.5 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268228
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 16717
telemt_upstream_connect_attempt_total 9800
telemt_upstream_connect_success_total 6962
telemt_upstream_connect_fail_total 2837
telemt_upstream_connect_attempts_per_request{bucket="1"} 9799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1926
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2837
telemt_me_keepalive_timeout_total 728
telemt_me_reconnect_attempts_total 4621
telemt_me_reconnect_success_total 3831
telemt_me_reader_eof_total 4008
telemt_me_idle_close_by_peer_total 4006
telemt_me_route_drop_no_conn_total 149114
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229617
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1191
telemt_desync_full_logged_total 329
telemt_desync_suppressed_total 862
telemt_desync_frames_bucket_total{bucket="1_2"} 399
telemt_desync_frames_bucket_total{bucket="3_10"} 410
telemt_desync_frames_bucket_total{bucket="gt_10"} 382
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3906
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3810
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 230999
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 2400043049 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 55804227826 (51.97 GB)
telemt_user_msgs_from_client{user="hello"} 5382
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 20729.3 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445116
telemt_connections_bad_total 1901
telemt_handshake_timeouts_total 32428
telemt_upstream_connect_attempt_total 6304
telemt_upstream_connect_success_total 6210
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 6304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 9704
telemt_me_reconnect_success_total 4074
telemt_me_reader_eof_total 4372
telemt_me_idle_close_by_peer_total 4372
telemt_me_route_drop_no_conn_total 153941
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 385221
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1311
telemt_desync_full_logged_total 361
telemt_desync_suppressed_total 950
telemt_desync_frames_bucket_total{bucket="1_2"} 301
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 566
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4324
telemt_me_refill_failed_total 174
telemt_me_writer_restored_same_endpoint_total 4063
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 386166
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 5547148809 (5.17 GB)
telemt_user_octets_to_client{user="hello"} 119790186481 (111.56 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 20729.9 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299333
telemt_connections_bad_total 20420
telemt_handshake_timeouts_total 26041
telemt_upstream_connect_attempt_total 5655
telemt_upstream_connect_success_total 5655
telemt_upstream_connect_attempts_per_request{bucket="1"} 5655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 5600
telemt_me_reconnect_success_total 4583
telemt_me_reader_eof_total 4789
telemt_me_idle_close_by_peer_total 4789
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 97554
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241196
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 653
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 388
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4661
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4570
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 240897
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 3704506932 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 74650985596 (69.52 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 20729.5 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314868
telemt_connections_bad_total 882
telemt_handshake_timeouts_total 2031
telemt_upstream_connect_attempt_total 6590
telemt_upstream_connect_success_total 6564
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 141
telemt_me_reconnect_attempts_total 6534
telemt_me_reconnect_success_total 5471
telemt_me_reader_eof_total 5648
telemt_me_idle_close_by_peer_total 5648
telemt_me_route_drop_no_conn_total 115421
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296689
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1692
telemt_desync_full_logged_total 631
telemt_desync_suppressed_total 1061
telemt_desync_frames_bucket_total{bucket="1_2"} 661
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 319
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5586
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 5471
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 296602
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 5720665552 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 98522446460 (91.76 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 69
```