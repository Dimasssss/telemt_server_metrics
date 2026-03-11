# Server Metrics 2026-03-11 20:33:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 108385.6 (30h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2749829
telemt_connections_bad_total 56827
telemt_handshake_timeouts_total 62188
telemt_upstream_connect_attempt_total 22942
telemt_upstream_connect_success_total 22930
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5412
telemt_me_reconnect_attempts_total 35325
telemt_me_reconnect_success_total 17431
telemt_me_reader_eof_total 18823
telemt_me_idle_close_by_peer_total 18823
telemt_me_route_drop_no_conn_total 1035336
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2501616
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12655
telemt_desync_full_logged_total 3513
telemt_desync_suppressed_total 9142
telemt_desync_frames_bucket_total{bucket="1_2"} 3119
telemt_desync_frames_bucket_total{bucket="3_10"} 4863
telemt_desync_frames_bucket_total{bucket="gt_10"} 4673
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 18193
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17425
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 762
telemt_user_connections_total{user="hello"} 2499958
telemt_user_connections_current{user="hello"} 932
telemt_user_octets_from_client{user="hello"} 37861445584 (35.26 GB)
telemt_user_octets_to_client{user="hello"} 719057051592 (669.67 GB)
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 108442.2 (30h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1010256
telemt_connections_bad_total 16867
telemt_handshake_timeouts_total 90404
telemt_upstream_connect_attempt_total 33171
telemt_upstream_connect_success_total 30198
telemt_upstream_connect_fail_total 2973
telemt_upstream_connect_attempts_per_request{bucket="1"} 33171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2089
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2973
telemt_me_keepalive_timeout_total 2887
telemt_me_reconnect_attempts_total 23913
telemt_me_reconnect_success_total 21788
telemt_me_reader_eof_total 23086
telemt_me_idle_close_by_peer_total 23083
telemt_me_route_drop_no_conn_total 382458
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 843681
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3350
telemt_desync_full_logged_total 1088
telemt_desync_suppressed_total 2262
telemt_desync_frames_bucket_total{bucket="1_2"} 1085
telemt_desync_frames_bucket_total{bucket="3_10"} 1182
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 22110
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21765
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 846122
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 10253536042 (9.55 GB)
telemt_user_octets_to_client{user="hello"} 248710516444 (231.63 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 108442.2 (30h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1756066
telemt_connections_bad_total 11107
telemt_handshake_timeouts_total 135361
telemt_upstream_connect_attempt_total 27483
telemt_upstream_connect_success_total 27133
telemt_upstream_connect_fail_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 27483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 350
telemt_me_keepalive_timeout_total 2030
telemt_me_reconnect_attempts_total 58314
telemt_me_reconnect_success_total 20562
telemt_me_reader_eof_total 22601
telemt_me_idle_close_by_peer_total 22601
telemt_me_route_drop_no_conn_total 638977
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1544180
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4169
telemt_desync_full_logged_total 1228
telemt_desync_suppressed_total 2941
telemt_desync_frames_bucket_total{bucket="1_2"} 970
telemt_desync_frames_bucket_total{bucket="3_10"} 1584
telemt_desync_frames_bucket_total{bucket="gt_10"} 1615
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22024
telemt_me_refill_failed_total 1174
telemt_me_writer_restored_same_endpoint_total 20550
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1462
telemt_user_connections_total{user="hello"} 1543810
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 19835069769 (18.47 GB)
telemt_user_octets_to_client{user="hello"} 473347152417 (440.84 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 108442.5 (30h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1255064
telemt_connections_bad_total 78240
telemt_handshake_timeouts_total 111440
telemt_upstream_connect_attempt_total 29169
telemt_upstream_connect_success_total 29169
telemt_upstream_connect_attempts_per_request{bucket="1"} 29169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1528
telemt_me_reconnect_attempts_total 28355
telemt_me_reconnect_success_total 23735
telemt_me_reader_eof_total 25202
telemt_me_idle_close_by_peer_total 25201
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 421843
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1029669
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2195
telemt_desync_full_logged_total 825
telemt_desync_suppressed_total 1370
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 24131
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23702
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 1028795
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 12192199628 (11.35 GB)
telemt_user_octets_to_client{user="hello"} 312887802572 (291.40 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13118.7 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193632
telemt_connections_bad_total 5148
telemt_handshake_timeouts_total 2227
telemt_upstream_connect_attempt_total 3782
telemt_upstream_connect_success_total 3781
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 3090
telemt_me_reconnect_success_total 3061
telemt_me_reader_eof_total 3158
telemt_me_idle_close_by_peer_total 3158
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 65365
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170402
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 428
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3098
telemt_me_writer_restored_same_endpoint_total 3036
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 170365
telemt_user_connections_current{user="hello"} 470
telemt_user_octets_from_client{user="hello"} 9521163576 (8.87 GB)
telemt_user_octets_to_client{user="hello"} 58306597392 (54.30 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 56
```