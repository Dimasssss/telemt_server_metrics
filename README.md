# Server Metrics 2026-03-11 21:24:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 111447.1 (30h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2813960
telemt_connections_bad_total 65568
telemt_handshake_timeouts_total 62607
telemt_upstream_connect_attempt_total 23773
telemt_upstream_connect_success_total 23761
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5443
telemt_me_reconnect_attempts_total 36025
telemt_me_reconnect_success_total 18126
telemt_me_reader_eof_total 19559
telemt_me_idle_close_by_peer_total 19559
telemt_me_route_drop_no_conn_total 1054902
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2550535
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12733
telemt_desync_full_logged_total 3539
telemt_desync_suppressed_total 9194
telemt_desync_frames_bucket_total{bucket="1_2"} 3146
telemt_desync_frames_bucket_total{bucket="3_10"} 4886
telemt_desync_frames_bucket_total{bucket="gt_10"} 4701
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 18896
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 18120
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 770
telemt_user_connections_total{user="hello"} 2548868
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 38804380112 (36.14 GB)
telemt_user_octets_to_client{user="hello"} 736795935440 (686.19 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 111503.8 (30h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1025136
telemt_connections_bad_total 17056
telemt_handshake_timeouts_total 90479
telemt_upstream_connect_attempt_total 33886
telemt_upstream_connect_success_total 30907
telemt_upstream_connect_fail_total 2979
telemt_upstream_connect_attempts_per_request{bucket="1"} 33886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2091
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2979
telemt_me_keepalive_timeout_total 2914
telemt_me_reconnect_attempts_total 24493
telemt_me_reconnect_success_total 22363
telemt_me_reader_eof_total 23698
telemt_me_idle_close_by_peer_total 23695
telemt_me_route_drop_no_conn_total 387679
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 857789
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3383
telemt_desync_full_logged_total 1102
telemt_desync_suppressed_total 2281
telemt_desync_frames_bucket_total{bucket="1_2"} 1106
telemt_desync_frames_bucket_total{bucket="3_10"} 1194
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 22693
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 22340
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 860225
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 10390818158 (9.68 GB)
telemt_user_octets_to_client{user="hello"} 260288129112 (242.41 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 111503.6 (30h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1791679
telemt_connections_bad_total 11436
telemt_handshake_timeouts_total 137422
telemt_upstream_connect_attempt_total 43340
telemt_upstream_connect_success_total 42981
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 43340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_keepalive_timeout_total 2059
telemt_me_reconnect_attempts_total 62573
telemt_me_reconnect_success_total 20689
telemt_me_reader_eof_total 22857
telemt_me_idle_close_by_peer_total 22857
telemt_me_route_drop_no_conn_total 646485
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1560723
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4213
telemt_desync_full_logged_total 1243
telemt_desync_suppressed_total 2970
telemt_desync_frames_bucket_total{bucket="1_2"} 986
telemt_desync_frames_bucket_total{bucket="3_10"} 1602
telemt_desync_frames_bucket_total{bucket="gt_10"} 1625
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22280
telemt_me_refill_failed_total 1303
telemt_me_writer_restored_same_endpoint_total 20677
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1591
telemt_user_connections_total{user="hello"} 1575931
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 20026203414 (18.65 GB)
telemt_user_octets_to_client{user="hello"} 481436606049 (448.37 GB)
telemt_user_msgs_from_client{user="hello"} 194158
telemt_user_msgs_to_client{user="hello"} 1187070
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 111504.2 (30h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1282183
telemt_connections_bad_total 78287
telemt_handshake_timeouts_total 111895
telemt_upstream_connect_attempt_total 29874
telemt_upstream_connect_success_total 29874
telemt_upstream_connect_attempts_per_request{bucket="1"} 29874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1555
telemt_me_reconnect_attempts_total 28929
telemt_me_reconnect_success_total 24308
telemt_me_reader_eof_total 25818
telemt_me_idle_close_by_peer_total 25817
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 430203
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1055997
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2212
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1380
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 24714
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24275
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 406
telemt_user_connections_total{user="hello"} 1055117
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 12348171888 (11.50 GB)
telemt_user_octets_to_client{user="hello"} 318658505856 (296.77 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 16180.1 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218543
telemt_connections_bad_total 5183
telemt_handshake_timeouts_total 2470
telemt_upstream_connect_attempt_total 4603
telemt_upstream_connect_success_total 4602
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 3781
telemt_me_reconnect_success_total 3746
telemt_me_reader_eof_total 3886
telemt_me_idle_close_by_peer_total 3886
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 74108
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193720
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 488
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3790
telemt_me_writer_restored_same_endpoint_total 3719
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 193682
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 9696786544 (9.03 GB)
telemt_user_octets_to_client{user="hello"} 66967628052 (62.37 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 50
```