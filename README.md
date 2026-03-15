# Server Metrics 2026-03-15 17:59:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 71127.7 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2519648
telemt_connections_bad_total 150072
telemt_handshake_timeouts_total 32989
telemt_upstream_connect_attempt_total 13759
telemt_upstream_connect_success_total 13700
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 13759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 15056
telemt_me_reconnect_success_total 10158
telemt_me_reader_eof_total 10856
telemt_me_idle_close_by_peer_total 10856
telemt_me_route_drop_no_conn_total 871749
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2103698
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8179
telemt_desync_full_logged_total 2225
telemt_desync_suppressed_total 5954
telemt_desync_frames_bucket_total{bucket="1_2"} 2008
telemt_desync_frames_bucket_total{bucket="3_10"} 3130
telemt_desync_frames_bucket_total{bucket="gt_10"} 3041
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10482
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10147
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 2103169
telemt_user_connections_current{user="hello"} 2395
telemt_user_octets_from_client{user="hello"} 31460644596 (29.30 GB)
telemt_user_octets_to_client{user="hello"} 800650150952 (745.66 GB)
telemt_user_unique_ips_current{user="hello"} 690
telemt_user_unique_ips_recent_window{user="hello"} 308
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 71128.0 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 976170
telemt_connections_bad_total 55170
telemt_handshake_timeouts_total 62981
telemt_upstream_connect_attempt_total 17702
telemt_upstream_connect_success_total 17607
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 17702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8087
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14912
telemt_me_reconnect_success_total 13702
telemt_me_reader_eof_total 14495
telemt_me_idle_close_by_peer_total 14495
telemt_me_route_drop_no_conn_total 252485
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 753573
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2207
telemt_desync_full_logged_total 746
telemt_desync_suppressed_total 1461
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 832
telemt_desync_frames_bucket_total{bucket="gt_10"} 597
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13918
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13690
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 753802
telemt_user_connections_current{user="hello"} 887
telemt_user_octets_from_client{user="hello"} 10965889019 (10.21 GB)
telemt_user_octets_to_client{user="hello"} 283093286304 (263.65 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 71128.3 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2154954
telemt_connections_bad_total 50493
telemt_handshake_timeouts_total 214803
telemt_upstream_connect_attempt_total 15288
telemt_upstream_connect_success_total 15213
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 15288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12908
telemt_me_reconnect_success_total 11639
telemt_me_reader_eof_total 12331
telemt_me_idle_close_by_peer_total 12331
telemt_me_route_drop_no_conn_total 558844
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1341915
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3475
telemt_desync_full_logged_total 1253
telemt_desync_suppressed_total 2222
telemt_desync_frames_bucket_total{bucket="1_2"} 787
telemt_desync_frames_bucket_total{bucket="3_10"} 1357
telemt_desync_frames_bucket_total{bucket="gt_10"} 1331
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11844
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11620
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 1337808
telemt_user_connections_current{user="hello"} 1462
telemt_user_octets_from_client{user="hello"} 24828557868 (23.12 GB)
telemt_user_octets_to_client{user="hello"} 494924252000 (460.93 GB)
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 71128.0 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1040236
telemt_connections_bad_total 82056
telemt_handshake_timeouts_total 50846
telemt_upstream_connect_attempt_total 170635
telemt_upstream_connect_success_total 170048
telemt_upstream_connect_fail_total 587
telemt_upstream_connect_attempts_per_request{bucket="1"} 170635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 587
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61600
telemt_me_reconnect_success_total 13535
telemt_me_reader_eof_total 15401
telemt_me_idle_close_by_peer_total 15401
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 246315
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 656385
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1842
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 1340
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 15181
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13499
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1646
telemt_user_connections_total{user="hello"} 808901
telemt_user_connections_current{user="hello"} 846
telemt_user_octets_from_client{user="hello"} 15107192769 (14.07 GB)
telemt_user_octets_to_client{user="hello"} 287995462028 (268.22 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 71128.8 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1053757
telemt_connections_bad_total 12565
telemt_handshake_timeouts_total 23261
telemt_upstream_connect_attempt_total 15606
telemt_upstream_connect_success_total 15523
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15664
telemt_me_reconnect_success_total 11969
telemt_me_reader_eof_total 12764
telemt_me_idle_close_by_peer_total 12764
telemt_me_route_drop_no_conn_total 262795
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 872959
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2982
telemt_desync_full_logged_total 998
telemt_desync_suppressed_total 1984
telemt_desync_frames_bucket_total{bucket="1_2"} 915
telemt_desync_frames_bucket_total{bucket="3_10"} 1101
telemt_desync_frames_bucket_total{bucket="gt_10"} 966
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12228
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11961
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 872982
telemt_user_connections_current{user="hello"} 982
telemt_user_octets_from_client{user="hello"} 10890535896 (10.14 GB)
telemt_user_octets_to_client{user="hello"} 307095954900 (286.01 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 118
```