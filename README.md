# Server Metrics 2026-03-14 18:16:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 17916.1 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 723610
telemt_connections_bad_total 38798
telemt_handshake_timeouts_total 9697
telemt_upstream_connect_attempt_total 3501
telemt_upstream_connect_success_total 3486
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 3350
telemt_me_reconnect_success_total 2549
telemt_me_reader_eof_total 2670
telemt_me_idle_close_by_peer_total 2670
telemt_me_route_drop_no_conn_total 277085
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642416
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2230
telemt_desync_full_logged_total 644
telemt_desync_suppressed_total 1586
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 845
telemt_desync_frames_bucket_total{bucket="gt_10"} 862
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2613
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2540
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 642349
telemt_user_connections_current{user="hello"} 1905
telemt_user_octets_from_client{user="hello"} 11141073652 (10.38 GB)
telemt_user_octets_to_client{user="hello"} 208588018596 (194.26 GB)
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 17921.3 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284240
telemt_connections_bad_total 22774
telemt_handshake_timeouts_total 8825
telemt_upstream_connect_attempt_total 3686
telemt_upstream_connect_success_total 3642
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 3686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 312
telemt_me_reconnect_attempts_total 3497
telemt_me_reconnect_success_total 2706
telemt_me_reader_eof_total 2832
telemt_me_idle_close_by_peer_total 2832
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 88564
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234889
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 919
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 630
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 222
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2790
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2691
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 234830
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 3282187440 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 87221220324 (81.23 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 17784.2 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 605212
telemt_connections_bad_total 2170
telemt_handshake_timeouts_total 127865
telemt_upstream_connect_attempt_total 3531
telemt_upstream_connect_success_total 3519
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1728
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6501
telemt_me_reconnect_success_total 2597
telemt_me_reader_eof_total 2792
telemt_me_idle_close_by_peer_total 2792
telemt_me_route_drop_no_conn_total 145967
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 404157
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1279
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 825
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 442
telemt_desync_frames_bucket_total{bucket="gt_10"} 656
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2742
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2564
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 404046
telemt_user_connections_current{user="hello"} 918
telemt_user_octets_from_client{user="hello"} 5917368200 (5.51 GB)
telemt_user_octets_to_client{user="hello"} 144445138004 (134.53 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 17638.5 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326869
telemt_connections_bad_total 76880
telemt_handshake_timeouts_total 41825
telemt_upstream_connect_attempt_total 4242
telemt_upstream_connect_success_total 4241
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 4241
telemt_me_reconnect_success_total 3326
telemt_me_reader_eof_total 3473
telemt_me_idle_close_by_peer_total 3473
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 72147
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203165
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 416
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 278
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3386
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3318
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 203117
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 3014231236 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 63131850896 (58.80 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 17934.4 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276628
telemt_connections_bad_total 1109
telemt_handshake_timeouts_total 3303
telemt_upstream_connect_attempt_total 3734
telemt_upstream_connect_success_total 3659
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 3734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 3410
telemt_me_reconnect_success_total 2743
telemt_me_reader_eof_total 2888
telemt_me_idle_close_by_peer_total 2888
telemt_me_route_drop_no_conn_total 87880
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255575
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 633
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2820
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2725
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 255561
telemt_user_connections_current{user="hello"} 886
telemt_user_octets_from_client{user="hello"} 3989609580 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 107990254368 (100.57 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 106
```