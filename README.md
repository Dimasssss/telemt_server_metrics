# Server Metrics 2026-03-15 17:29:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 69287.3 (19h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2424219
telemt_connections_bad_total 148332
telemt_handshake_timeouts_total 30856
telemt_upstream_connect_attempt_total 13479
telemt_upstream_connect_success_total 13421
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 13479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 14866
telemt_me_reconnect_success_total 9969
telemt_me_reader_eof_total 10656
telemt_me_idle_close_by_peer_total 10656
telemt_me_route_drop_no_conn_total 834189
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2022638
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7910
telemt_desync_full_logged_total 2143
telemt_desync_suppressed_total 5767
telemt_desync_frames_bucket_total{bucket="1_2"} 1918
telemt_desync_frames_bucket_total{bucket="3_10"} 3044
telemt_desync_frames_bucket_total{bucket="gt_10"} 2948
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10290
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9958
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 321
telemt_user_connections_total{user="hello"} 2022121
telemt_user_connections_current{user="hello"} 2427
telemt_user_octets_from_client{user="hello"} 29848399888 (27.80 GB)
telemt_user_octets_to_client{user="hello"} 767089664712 (714.41 GB)
telemt_user_unique_ips_current{user="hello"} 713
telemt_user_unique_ips_recent_window{user="hello"} 321
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 69287.7 (19h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 934894
telemt_connections_bad_total 50181
telemt_handshake_timeouts_total 62109
telemt_upstream_connect_attempt_total 17333
telemt_upstream_connect_success_total 17241
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 17333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7904
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14638
telemt_me_reconnect_success_total 13431
telemt_me_reader_eof_total 14207
telemt_me_idle_close_by_peer_total 14207
telemt_me_route_drop_no_conn_total 241531
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 723215
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2187
telemt_desync_full_logged_total 734
telemt_desync_suppressed_total 1453
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 825
telemt_desync_frames_bucket_total{bucket="gt_10"} 587
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13644
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13419
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 723450
telemt_user_connections_current{user="hello"} 888
telemt_user_octets_from_client{user="hello"} 10547990963 (9.82 GB)
telemt_user_octets_to_client{user="hello"} 273302506756 (254.53 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 69287.9 (19h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2092042
telemt_connections_bad_total 49677
telemt_handshake_timeouts_total 212898
telemt_upstream_connect_attempt_total 14990
telemt_upstream_connect_success_total 14920
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 14990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12705
telemt_me_reconnect_success_total 11436
telemt_me_reader_eof_total 12115
telemt_me_idle_close_by_peer_total 12115
telemt_me_route_drop_no_conn_total 542008
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1288171
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3288
telemt_desync_full_logged_total 1188
telemt_desync_suppressed_total 2100
telemt_desync_frames_bucket_total{bucket="1_2"} 756
telemt_desync_frames_bucket_total{bucket="3_10"} 1271
telemt_desync_frames_bucket_total{bucket="gt_10"} 1261
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11638
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11417
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 1284100
telemt_user_connections_current{user="hello"} 1551
telemt_user_octets_from_client{user="hello"} 20986506116 (19.55 GB)
telemt_user_octets_to_client{user="hello"} 460580134224 (428.95 GB)
telemt_user_unique_ips_current{user="hello"} 421
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 69287.6 (19h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1004795
telemt_connections_bad_total 82045
telemt_handshake_timeouts_total 48684
telemt_upstream_connect_attempt_total 170396
telemt_upstream_connect_success_total 169827
telemt_upstream_connect_fail_total 569
telemt_upstream_connect_attempts_per_request{bucket="1"} 170396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 569
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 60107
telemt_me_reconnect_success_total 13403
telemt_me_reader_eof_total 15222
telemt_me_idle_close_by_peer_total 15222
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 234000
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 623781
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1775
telemt_desync_full_logged_total 479
telemt_desync_suppressed_total 1296
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 685
telemt_desync_frames_bucket_total{bucket="gt_10"} 634
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 15004
telemt_me_refill_failed_total 1461
telemt_me_writer_restored_same_endpoint_total 13367
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1601
telemt_user_connections_total{user="hello"} 776302
telemt_user_connections_current{user="hello"} 890
telemt_user_octets_from_client{user="hello"} 14428490465 (13.44 GB)
telemt_user_octets_to_client{user="hello"} 277398697088 (258.35 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 69288.7 (19h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1014914
telemt_connections_bad_total 12073
telemt_handshake_timeouts_total 22884
telemt_upstream_connect_attempt_total 15285
telemt_upstream_connect_success_total 15202
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15435
telemt_me_reconnect_success_total 11740
telemt_me_reader_eof_total 12522
telemt_me_idle_close_by_peer_total 12522
telemt_me_route_drop_no_conn_total 253003
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 839610
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2835
telemt_desync_full_logged_total 954
telemt_desync_suppressed_total 1881
telemt_desync_frames_bucket_total{bucket="1_2"} 872
telemt_desync_frames_bucket_total{bucket="3_10"} 1057
telemt_desync_frames_bucket_total{bucket="gt_10"} 906
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 11998
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11732
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 839640
telemt_user_connections_current{user="hello"} 949
telemt_user_octets_from_client{user="hello"} 10466768792 (9.75 GB)
telemt_user_octets_to_client{user="hello"} 296251944216 (275.91 GB)
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 121
```