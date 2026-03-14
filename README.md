# Server Metrics 2026-03-14 18:31:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 18836.7 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 763776
telemt_connections_bad_total 39615
telemt_handshake_timeouts_total 10529
telemt_upstream_connect_attempt_total 3625
telemt_upstream_connect_success_total 3610
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 3428
telemt_me_reconnect_success_total 2627
telemt_me_reader_eof_total 2756
telemt_me_idle_close_by_peer_total 2756
telemt_me_route_drop_no_conn_total 292883
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 676582
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2349
telemt_desync_full_logged_total 675
telemt_desync_suppressed_total 1674
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 884
telemt_desync_frames_bucket_total{bucket="gt_10"} 903
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2693
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2618
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 676517
telemt_user_connections_current{user="hello"} 1869
telemt_user_octets_from_client{user="hello"} 11722765408 (10.92 GB)
telemt_user_octets_to_client{user="hello"} 221821867248 (206.59 GB)
telemt_user_unique_ips_current{user="hello"} 486
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 18841.9 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296469
telemt_connections_bad_total 22782
telemt_handshake_timeouts_total 8933
telemt_upstream_connect_attempt_total 3863
telemt_upstream_connect_success_total 3815
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 3863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 316
telemt_me_reconnect_attempts_total 3625
telemt_me_reconnect_success_total 2834
telemt_me_reader_eof_total 2969
telemt_me_idle_close_by_peer_total 2969
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 92693
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246378
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 994
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 685
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 374
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2921
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2819
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 246319
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 3445123276 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 89948586268 (83.77 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 18705.0 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 628106
telemt_connections_bad_total 2171
telemt_handshake_timeouts_total 130148
telemt_upstream_connect_attempt_total 3698
telemt_upstream_connect_success_total 3685
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1812
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6624
telemt_me_reconnect_success_total 2718
telemt_me_reader_eof_total 2922
telemt_me_idle_close_by_peer_total 2922
telemt_me_route_drop_no_conn_total 152141
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423146
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1401
telemt_desync_full_logged_total 530
telemt_desync_suppressed_total 871
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 482
telemt_desync_frames_bucket_total{bucket="gt_10"} 729
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2865
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2685
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 423053
telemt_user_connections_current{user="hello"} 1005
telemt_user_octets_from_client{user="hello"} 6097206192 (5.68 GB)
telemt_user_octets_to_client{user="hello"} 151778159036 (141.35 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 18559.3 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342605
telemt_connections_bad_total 80884
telemt_handshake_timeouts_total 42513
telemt_upstream_connect_attempt_total 4478
telemt_upstream_connect_success_total 4477
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 4434
telemt_me_reconnect_success_total 3518
telemt_me_reader_eof_total 3667
telemt_me_idle_close_by_peer_total 3667
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 75862
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213774
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 445
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3582
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3508
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 213725
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 3174892864 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 67389826196 (62.76 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 18854.9 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289841
telemt_connections_bad_total 1121
telemt_handshake_timeouts_total 3391
telemt_upstream_connect_attempt_total 3881
telemt_upstream_connect_success_total 3804
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 3881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 3512
telemt_me_reconnect_success_total 2844
telemt_me_reader_eof_total 2998
telemt_me_idle_close_by_peer_total 2998
telemt_me_route_drop_no_conn_total 91421
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267960
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 643
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2923
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2826
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 267947
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 4150254952 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 116945162488 (108.91 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 94
```