# Server Metrics 2026-03-11 21:44:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 112671.2 (31h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2830933
telemt_connections_bad_total 66253
telemt_handshake_timeouts_total 62650
telemt_upstream_connect_attempt_total 24065
telemt_upstream_connect_success_total 24053
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 24065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5453
telemt_me_reconnect_attempts_total 36231
telemt_me_reconnect_success_total 18329
telemt_me_reader_eof_total 19784
telemt_me_idle_close_by_peer_total 19784
telemt_me_route_drop_no_conn_total 1060489
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2564627
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12758
telemt_desync_full_logged_total 3545
telemt_desync_suppressed_total 9213
telemt_desync_frames_bucket_total{bucket="1_2"} 3151
telemt_desync_frames_bucket_total{bucket="3_10"} 4895
telemt_desync_frames_bucket_total{bucket="gt_10"} 4712
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 19102
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 18323
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 773
telemt_user_connections_total{user="hello"} 2562960
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 38900864640 (36.23 GB)
telemt_user_octets_to_client{user="hello"} 740184893272 (689.35 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 112727.9 (31h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1031579
telemt_connections_bad_total 17056
telemt_handshake_timeouts_total 90615
telemt_upstream_connect_attempt_total 34744
telemt_upstream_connect_success_total 31752
telemt_upstream_connect_fail_total 2992
telemt_upstream_connect_attempts_per_request{bucket="1"} 34744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2093
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2992
telemt_me_keepalive_timeout_total 6551
telemt_me_reconnect_attempts_total 24971
telemt_me_reconnect_success_total 22826
telemt_me_reader_eof_total 24148
telemt_me_idle_close_by_peer_total 24145
telemt_me_route_drop_no_conn_total 389365
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 863635
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3385
telemt_desync_full_logged_total 1103
telemt_desync_suppressed_total 2282
telemt_desync_frames_bucket_total{bucket="1_2"} 1108
telemt_desync_frames_bucket_total{bucket="3_10"} 1194
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 23107
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 22803
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 141
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 866363
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 10450384553 (9.73 GB)
telemt_user_octets_to_client{user="hello"} 261715219732 (243.74 GB)
telemt_user_msgs_from_client{user="hello"} 8579
telemt_user_msgs_to_client{user="hello"} 12990
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 112727.5 (31h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1804053
telemt_connections_bad_total 11437
telemt_handshake_timeouts_total 138283
telemt_upstream_connect_attempt_total 52171
telemt_upstream_connect_success_total 51805
telemt_upstream_connect_fail_total 366
telemt_upstream_connect_attempts_per_request{bucket="1"} 52171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13672
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 366
telemt_me_keepalive_timeout_total 2079
telemt_me_reconnect_attempts_total 65363
telemt_me_reconnect_success_total 20727
telemt_me_reader_eof_total 22981
telemt_me_idle_close_by_peer_total 22981
telemt_me_route_drop_no_conn_total 647683
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1563214
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4216
telemt_desync_full_logged_total 1245
telemt_desync_suppressed_total 2971
telemt_desync_frames_bucket_total{bucket="1_2"} 987
telemt_desync_frames_bucket_total{bucket="3_10"} 1604
telemt_desync_frames_bucket_total{bucket="gt_10"} 1625
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22404
telemt_me_refill_failed_total 1389
telemt_me_writer_restored_same_endpoint_total 20715
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1677
telemt_user_connections_total{user="hello"} 1587120
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 20122600167 (18.74 GB)
telemt_user_octets_to_client{user="hello"} 484277975086 (451.02 GB)
telemt_user_msgs_from_client{user="hello"} 294490
telemt_user_msgs_to_client{user="hello"} 2028493
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 112727.9 (31h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1290816
telemt_connections_bad_total 78309
telemt_handshake_timeouts_total 112122
telemt_upstream_connect_attempt_total 30190
telemt_upstream_connect_success_total 30190
telemt_upstream_connect_attempts_per_request{bucket="1"} 30190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13753
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1557
telemt_me_reconnect_attempts_total 29159
telemt_me_reconnect_success_total 24535
telemt_me_reader_eof_total 26056
telemt_me_idle_close_by_peer_total 26055
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 432196
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1064312
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 35
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
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 24944
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24501
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 409
telemt_user_connections_total{user="hello"} 1063432
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 12434688560 (11.58 GB)
telemt_user_octets_to_client{user="hello"} 320369733780 (298.37 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17403.9 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225989
telemt_connections_bad_total 5185
telemt_handshake_timeouts_total 2545
telemt_upstream_connect_attempt_total 5051
telemt_upstream_connect_success_total 5050
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 4141
telemt_me_reconnect_success_total 4103
telemt_me_reader_eof_total 4264
telemt_me_idle_close_by_peer_total 4264
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 76174
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200726
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 510
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 330
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4150
telemt_me_writer_restored_same_endpoint_total 4076
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 200688
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 9754923900 (9.08 GB)
telemt_user_octets_to_client{user="hello"} 69913674036 (65.11 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 44
```