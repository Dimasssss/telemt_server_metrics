# Server Metrics 2026-03-15 16:53:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 67141.0 (18h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2289423
telemt_connections_bad_total 135796
telemt_handshake_timeouts_total 28401
telemt_upstream_connect_attempt_total 13207
telemt_upstream_connect_success_total 13150
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 13207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14681
telemt_me_reconnect_success_total 9784
telemt_me_reader_eof_total 10456
telemt_me_idle_close_by_peer_total 10456
telemt_me_route_drop_no_conn_total 790992
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1924335
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7575
telemt_desync_full_logged_total 2066
telemt_desync_suppressed_total 5509
telemt_desync_frames_bucket_total{bucket="1_2"} 1834
telemt_desync_frames_bucket_total{bucket="3_10"} 2910
telemt_desync_frames_bucket_total{bucket="gt_10"} 2831
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10098
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9773
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 1923827
telemt_user_connections_current{user="hello"} 2535
telemt_user_octets_from_client{user="hello"} 28318763348 (26.37 GB)
telemt_user_octets_to_client{user="hello"} 730635853160 (680.46 GB)
telemt_user_unique_ips_current{user="hello"} 713
telemt_user_unique_ips_recent_window{user="hello"} 331
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 67141.8 (18h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 891467
telemt_connections_bad_total 47440
telemt_handshake_timeouts_total 61113
telemt_upstream_connect_attempt_total 16964
telemt_upstream_connect_success_total 16881
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 16964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14359
telemt_me_reconnect_success_total 13164
telemt_me_reader_eof_total 13931
telemt_me_idle_close_by_peer_total 13931
telemt_me_route_drop_no_conn_total 229317
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 685674
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2167
telemt_desync_full_logged_total 727
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 774
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13373
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13152
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 685916
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 9848793543 (9.17 GB)
telemt_user_octets_to_client{user="hello"} 259639716296 (241.81 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 67141.9 (18h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2010301
telemt_connections_bad_total 48509
telemt_handshake_timeouts_total 198251
telemt_upstream_connect_attempt_total 14677
telemt_upstream_connect_success_total 14608
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 14677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12479
telemt_me_reconnect_success_total 11211
telemt_me_reader_eof_total 11876
telemt_me_idle_close_by_peer_total 11876
telemt_me_route_drop_no_conn_total 519698
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1224833
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3121
telemt_desync_full_logged_total 1123
telemt_desync_suppressed_total 1998
telemt_desync_frames_bucket_total{bucket="1_2"} 723
telemt_desync_frames_bucket_total{bucket="3_10"} 1201
telemt_desync_frames_bucket_total{bucket="gt_10"} 1197
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11409
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11192
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 1220788
telemt_user_connections_current{user="hello"} 1419
telemt_user_octets_from_client{user="hello"} 18722488724 (17.44 GB)
telemt_user_octets_to_client{user="hello"} 437442613112 (407.40 GB)
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 67141.7 (18h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 953428
telemt_connections_bad_total 80301
telemt_handshake_timeouts_total 47057
telemt_upstream_connect_attempt_total 169203
telemt_upstream_connect_success_total 168667
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 169203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 57407
telemt_me_reconnect_success_total 13233
telemt_me_reader_eof_total 14971
telemt_me_idle_close_by_peer_total 14971
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 218836
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 583943
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1661
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1226
telemt_desync_frames_bucket_total{bucket="1_2"} 430
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14748
telemt_me_refill_failed_total 1382
telemt_me_writer_restored_same_endpoint_total 13197
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1515
telemt_user_connections_total{user="hello"} 735567
telemt_user_connections_current{user="hello"} 944
telemt_user_octets_from_client{user="hello"} 13884492046 (12.93 GB)
telemt_user_octets_to_client{user="hello"} 263387082081 (245.30 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 67142.6 (18h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 965654
telemt_connections_bad_total 12057
telemt_handshake_timeouts_total 21261
telemt_upstream_connect_attempt_total 14952
telemt_upstream_connect_success_total 14871
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 14952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 15189
telemt_me_reconnect_success_total 11498
telemt_me_reader_eof_total 12262
telemt_me_idle_close_by_peer_total 12262
telemt_me_route_drop_no_conn_total 241303
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 798920
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2725
telemt_desync_full_logged_total 916
telemt_desync_suppressed_total 1809
telemt_desync_frames_bucket_total{bucket="1_2"} 846
telemt_desync_frames_bucket_total{bucket="3_10"} 1019
telemt_desync_frames_bucket_total{bucket="gt_10"} 860
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 11751
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11490
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 798962
telemt_user_connections_current{user="hello"} 957
telemt_user_octets_from_client{user="hello"} 9877815340 (9.20 GB)
telemt_user_octets_to_client{user="hello"} 283652756400 (264.17 GB)
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 119
```