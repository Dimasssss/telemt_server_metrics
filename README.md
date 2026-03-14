# Server Metrics 2026-03-14 18:52:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 20063.7 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 808004
telemt_connections_bad_total 40349
telemt_handshake_timeouts_total 11585
telemt_upstream_connect_attempt_total 3842
telemt_upstream_connect_success_total 3826
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3558
telemt_me_reconnect_success_total 2755
telemt_me_reader_eof_total 2896
telemt_me_idle_close_by_peer_total 2896
telemt_me_route_drop_no_conn_total 310277
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 716026
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2459
telemt_desync_full_logged_total 708
telemt_desync_suppressed_total 1751
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 911
telemt_desync_frames_bucket_total{bucket="gt_10"} 956
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2825
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2746
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 715956
telemt_user_connections_current{user="hello"} 1693
telemt_user_octets_from_client{user="hello"} 12595142648 (11.73 GB)
telemt_user_octets_to_client{user="hello"} 237900556524 (221.56 GB)
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 20069.0 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313338
telemt_connections_bad_total 23055
telemt_handshake_timeouts_total 9198
telemt_upstream_connect_attempt_total 4236
telemt_upstream_connect_success_total 4185
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 4236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1862
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 383
telemt_me_reconnect_attempts_total 3909
telemt_me_reconnect_success_total 3116
telemt_me_reader_eof_total 3264
telemt_me_idle_close_by_peer_total 3264
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 97732
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262320
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1076
telemt_desync_full_logged_total 332
telemt_desync_suppressed_total 744
telemt_desync_frames_bucket_total{bucket="1_2"} 422
telemt_desync_frames_bucket_total{bucket="3_10"} 400
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3206
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3100
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 262243
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 3676958668 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 94082386268 (87.62 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 19931.8 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 656279
telemt_connections_bad_total 2462
telemt_handshake_timeouts_total 131165
telemt_upstream_connect_attempt_total 3932
telemt_upstream_connect_success_total 3919
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 6772
telemt_me_reconnect_success_total 2865
telemt_me_reader_eof_total 3076
telemt_me_idle_close_by_peer_total 3076
telemt_me_route_drop_no_conn_total 159836
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 446760
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1531
telemt_desync_full_logged_total 593
telemt_desync_suppressed_total 938
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 529
telemt_desync_frames_bucket_total{bucket="gt_10"} 796
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3012
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2832
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 446666
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 6522573244 (6.07 GB)
telemt_user_octets_to_client{user="hello"} 159281491672 (148.34 GB)
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 19786.4 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361858
telemt_connections_bad_total 84449
telemt_handshake_timeouts_total 43828
telemt_upstream_connect_attempt_total 4719
telemt_upstream_connect_success_total 4718
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 4629
telemt_me_reconnect_success_total 3713
telemt_me_reader_eof_total 3876
telemt_me_idle_close_by_peer_total 3876
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 80747
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227701
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 497
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 329
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3782
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3703
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 227639
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 3370105488 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 71248664080 (66.36 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 20082.2 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307298
telemt_connections_bad_total 1232
telemt_handshake_timeouts_total 3468
telemt_upstream_connect_attempt_total 4147
telemt_upstream_connect_success_total 4062
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 4147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2006
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 3682
telemt_me_reconnect_success_total 3013
telemt_me_reader_eof_total 3182
telemt_me_idle_close_by_peer_total 3182
telemt_me_route_drop_no_conn_total 96136
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284596
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 698
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 254
telemt_desync_frames_bucket_total{bucket="3_10"} 212
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3095
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2995
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 284581
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 4399955204 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 122354709760 (113.95 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 94
```