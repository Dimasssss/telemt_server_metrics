# Server Metrics 2026-03-06 09:14:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 2582.7 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73524
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 190
telemt_upstream_connect_attempt_total 771
telemt_upstream_connect_success_total 767
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 355
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 7
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 18964
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 377
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 58031
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 892160656 (850.83 MB)
telemt_user_octets_to_client{user="hello"} 19228671524 (17.91 GB)
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 2580.1 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49888
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 24407
telemt_upstream_connect_attempt_total 891
telemt_upstream_connect_success_total 891
telemt_upstream_connect_attempts_per_request{bucket="1"} 891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 444
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18
telemt_me_reconnect_success_total 16
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 8996
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 108
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_me_writer_removed_unexpected_total 18
telemt_me_writer_restored_same_endpoint_total 16
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 23573
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 381543304 (363.87 MB)
telemt_user_octets_to_client{user="hello"} 8595686932 (8.01 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 2563.2 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53318
telemt_connections_bad_total 264
telemt_handshake_timeouts_total 8490
telemt_upstream_connect_attempt_total 973
telemt_upstream_connect_success_total 963
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 57
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 51
telemt_me_idle_close_by_peer_total 50
telemt_me_route_drop_no_conn_total 15799
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 109
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_me_writer_removed_unexpected_total 52
telemt_me_writer_restored_same_endpoint_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 42894
telemt_user_connections_current{user="hello"} 710
telemt_user_octets_from_client{user="hello"} 797105140 (760.18 MB)
telemt_user_octets_to_client{user="hello"} 13166402684 (12.26 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 2547.9 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44683
telemt_connections_bad_total 2291
telemt_handshake_timeouts_total 10884
telemt_upstream_connect_attempt_total 964
telemt_upstream_connect_success_total 955
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 411
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 29
telemt_me_reconnect_success_total 27
telemt_me_reader_eof_total 27
telemt_me_idle_close_by_peer_total 27
telemt_me_route_drop_no_conn_total 16198
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 118
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_me_writer_removed_unexpected_total 27
telemt_me_writer_restored_same_endpoint_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 30347
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 628325484 (599.22 MB)
telemt_user_octets_to_client{user="hello"} 9792476756 (9.12 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 2489.5 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38630
telemt_connections_bad_total 260
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 968
telemt_upstream_connect_success_total 951
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 77
telemt_me_reconnect_success_total 80
telemt_me_reader_eof_total 75
telemt_me_idle_close_by_peer_total 75
telemt_me_route_drop_no_conn_total 15629
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 56
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_me_writer_removed_unexpected_total 75
telemt_me_writer_restored_same_endpoint_total 75
telemt_user_connections_total{user="hello"} 34641
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 679235296 (647.77 MB)
telemt_user_octets_to_client{user="hello"} 14890308040 (13.87 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 81
```