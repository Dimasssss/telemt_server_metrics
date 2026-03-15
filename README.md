# Server Metrics 2026-03-15 17:03:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 67753.7 (18h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2325371
telemt_connections_bad_total 138001
telemt_handshake_timeouts_total 29009
telemt_upstream_connect_attempt_total 13317
telemt_upstream_connect_success_total 13260
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 13317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14748
telemt_me_reconnect_success_total 9851
telemt_me_reader_eof_total 10530
telemt_me_idle_close_by_peer_total 10530
telemt_me_route_drop_no_conn_total 804045
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1953011
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7686
telemt_desync_full_logged_total 2088
telemt_desync_suppressed_total 5598
telemt_desync_frames_bucket_total{bucket="1_2"} 1867
telemt_desync_frames_bucket_total{bucket="3_10"} 2951
telemt_desync_frames_bucket_total{bucket="gt_10"} 2868
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10167
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9840
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 1952504
telemt_user_connections_current{user="hello"} 2539
telemt_user_octets_from_client{user="hello"} 28672436048 (26.70 GB)
telemt_user_octets_to_client{user="hello"} 741677414940 (690.74 GB)
telemt_user_unique_ips_current{user="hello"} 718
telemt_user_unique_ips_recent_window{user="hello"} 330
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 67754.5 (18h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 903812
telemt_connections_bad_total 47805
telemt_handshake_timeouts_total 61492
telemt_upstream_connect_attempt_total 17093
telemt_upstream_connect_success_total 17008
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 17093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14443
telemt_me_reconnect_success_total 13246
telemt_me_reader_eof_total 14019
telemt_me_idle_close_by_peer_total 14019
telemt_me_route_drop_no_conn_total 233209
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 696809
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2168
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 774
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 584
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13456
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13234
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 697051
telemt_user_connections_current{user="hello"} 876
telemt_user_octets_from_client{user="hello"} 10022526231 (9.33 GB)
telemt_user_octets_to_client{user="hello"} 263775444904 (245.66 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 67754.3 (18h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2034094
telemt_connections_bad_total 49212
telemt_handshake_timeouts_total 201576
telemt_upstream_connect_attempt_total 14794
telemt_upstream_connect_success_total 14725
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 14794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12553
telemt_me_reconnect_success_total 11283
telemt_me_reader_eof_total 11955
telemt_me_idle_close_by_peer_total 11955
telemt_me_route_drop_no_conn_total 527036
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1243699
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3190
telemt_desync_full_logged_total 1143
telemt_desync_suppressed_total 2047
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 1237
telemt_desync_frames_bucket_total{bucket="gt_10"} 1219
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11482
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11264
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 1239629
telemt_user_connections_current{user="hello"} 1365
telemt_user_octets_from_client{user="hello"} 18986590896 (17.68 GB)
telemt_user_octets_to_client{user="hello"} 443919486528 (413.43 GB)
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 67754.3 (18h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 966620
telemt_connections_bad_total 80844
telemt_handshake_timeouts_total 47597
telemt_upstream_connect_attempt_total 169326
telemt_upstream_connect_success_total 168778
telemt_upstream_connect_fail_total 548
telemt_upstream_connect_attempts_per_request{bucket="1"} 169326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13063
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 548
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 58723
telemt_me_reconnect_success_total 13300
telemt_me_reader_eof_total 15075
telemt_me_idle_close_by_peer_total 15075
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 223934
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595315
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1691
telemt_desync_full_logged_total 446
telemt_desync_suppressed_total 1245
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 657
telemt_desync_frames_bucket_total{bucket="gt_10"} 599
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14858
telemt_me_refill_failed_total 1421
telemt_me_writer_restored_same_endpoint_total 13264
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1558
telemt_user_connections_total{user="hello"} 746940
telemt_user_connections_current{user="hello"} 984
telemt_user_octets_from_client{user="hello"} 14084217862 (13.12 GB)
telemt_user_octets_to_client{user="hello"} 268303417481 (249.88 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 67755.1 (18h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 979853
telemt_connections_bad_total 12062
telemt_handshake_timeouts_total 21791
telemt_upstream_connect_attempt_total 15071
telemt_upstream_connect_success_total 14989
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 15264
telemt_me_reconnect_success_total 11571
telemt_me_reader_eof_total 12344
telemt_me_idle_close_by_peer_total 12344
telemt_me_route_drop_no_conn_total 244903
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 810655
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2754
telemt_desync_full_logged_total 926
telemt_desync_suppressed_total 1828
telemt_desync_frames_bucket_total{bucket="1_2"} 850
telemt_desync_frames_bucket_total{bucket="3_10"} 1030
telemt_desync_frames_bucket_total{bucket="gt_10"} 874
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 11826
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11563
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 810695
telemt_user_connections_current{user="hello"} 1082
telemt_user_octets_from_client{user="hello"} 9996318552 (9.31 GB)
telemt_user_octets_to_client{user="hello"} 287536719432 (267.79 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 157
```