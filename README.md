# Server Metrics 2026-03-12 03:41:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 21419.2 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187509
telemt_connections_bad_total 1367
telemt_handshake_timeouts_total 3389
telemt_upstream_connect_attempt_total 4901
telemt_upstream_connect_success_total 4901
telemt_upstream_connect_attempts_per_request{bucket="1"} 4901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 3838
telemt_me_reconnect_success_total 3822
telemt_me_reader_eof_total 4034
telemt_me_idle_close_by_peer_total 4034
telemt_me_route_drop_no_conn_total 67439
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177563
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 357
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3862
telemt_me_writer_restored_same_endpoint_total 3806
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 177354
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 1598748248 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 55224778244 (51.43 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 21419.9 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62154
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1113
telemt_upstream_connect_attempt_total 6074
telemt_upstream_connect_success_total 6071
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 4828
telemt_me_reconnect_success_total 4797
telemt_me_reader_eof_total 5088
telemt_me_idle_close_by_peer_total 5088
telemt_me_route_drop_no_conn_total 17716
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58113
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 74
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4833
telemt_me_writer_restored_same_endpoint_total 4788
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 58291
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 989632503 (943.79 MB)
telemt_user_octets_to_client{user="hello"} 20287869278 (18.89 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 21419.8 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327568
telemt_connections_bad_total 1548
telemt_handshake_timeouts_total 19263
telemt_upstream_connect_attempt_total 6409
telemt_upstream_connect_success_total 6407
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2739
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 5021
telemt_me_reconnect_success_total 4965
telemt_me_reader_eof_total 5169
telemt_me_idle_close_by_peer_total 5169
telemt_me_route_drop_no_conn_total 33769
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107981
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 311
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4929
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4924
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 108301
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 908267200 (866.19 MB)
telemt_user_octets_to_client{user="hello"} 33302475561 (31.02 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 21420.1 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96674
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 5033
telemt_upstream_connect_attempt_total 6395
telemt_upstream_connect_success_total 6367
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 5304
telemt_me_reconnect_success_total 5285
telemt_me_reader_eof_total 5601
telemt_me_idle_close_by_peer_total 5601
telemt_me_route_drop_no_conn_total 32859
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90155
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 142
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5318
telemt_me_writer_restored_same_endpoint_total 5264
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 90140
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 681211444 (649.65 MB)
telemt_user_octets_to_client{user="hello"} 23064438472 (21.48 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 21419.7 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115977
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 711
telemt_upstream_connect_attempt_total 7836
telemt_upstream_connect_success_total 7754
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 7836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 8158
telemt_me_reconnect_success_total 6659
telemt_me_reader_eof_total 6917
telemt_me_idle_close_by_peer_total 6917
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 30348
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110771
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 416
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 273
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 6753
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 6643
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 110747
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 685916840 (654.14 MB)
telemt_user_octets_to_client{user="hello"} 24053422936 (22.40 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 54
```